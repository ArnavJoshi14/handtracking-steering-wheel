# Hand Gesture Steering Controller
---
This is a personal Python project that uses your webcam and hand gestures to simulate steering, acceleration, braking, and reversing in a game.

It uses **MediaPipe** for hand tracking and **directkeys** for sending key presses.

## Requirements
---
* Python 3.x
* A webcam
* Windows OS (the `directkeys` module is Windows-specific)

Install dependencies:
`pip install -r requirements.txt`

## How to Run
---
Make sure your webcam is connected.

Open a terminal in this project's folder.

Run:
`python main.py`

The webcam window will open. Use your hands to control:

* **Both fists** → Accelerate (W)
* **Both palms** → Reverse (S)
* **One fist + one palm** → Brake (SPACE)
* **Tilt difference between left/right hands** → Steer left (A) or right (D)

Press **Q** to quit.

## Notes
---
This is a fun personal experiment — it won't work in every game.

Make sure your game accepts keyboard inputs for driving.
