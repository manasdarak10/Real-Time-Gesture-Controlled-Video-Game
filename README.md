# 🎮 Real-Time Gesture Controlled Video Game

A real-time Python-based game that uses your **hand gestures captured via webcam** to control game interactions. The project leverages **MediaPipe** for hand tracking and **OpenCV** for processing the video feed and displaying the interface.

## 🚀 Features
- Real-time webcam-based input
- Hand landmark detection using MediaPipe
- Control game states using gestures (e.g., start/stop)
- Fun, interactive, and contactless gaming experience
- Fully implemented in Python using minimal dependencies

## 📁 Project Structure
```
Real-Time-Gesture-Controlled-Video-Game/
├── main.py               # Main game loop and gesture handling
├── handtracker.py        # Hand tracking logic using MediaPipe
├── README.md             # Documentation
└── requirements.txt      # Python dependencies
```

## 🧠 How It Works
- `main.py` captures the webcam feed using OpenCV.
- Each frame is processed by `handtracker.py`, which uses MediaPipe to detect hand landmarks.
- Based on detected hand gestures (e.g., open palm, number of fingers), actions are triggered inside the game.
- The game can start, stop, or respond to specific hand positions or motions.

## 📦 Installation

### Step 1: Clone the repository
```bash
git clone https://github.com/manasdarak10/Real-Time-Gesture-Controlled-Video-Game.git
cd Real-Time-Gesture-Controlled-Video-Game
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

## ▶️ How to Run
Make sure your webcam is connected and accessible.
```bash
python main.py
```
Use your hand gestures in front of the webcam to interact with the game.

## 🛠️ Tech Stack
- Python 3.8+
- OpenCV
- MediaPipe
- NumPy
