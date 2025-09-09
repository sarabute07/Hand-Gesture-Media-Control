# Hand-Gesture-Media-Control

## Project Overview
This project uses computer vision to detect a yellow object using a webcam.  
When the object moves upward, it triggers a key press (spacebar) using `pyautogui`.

## Features
- Real-time yellow object detection
- Draws contours around the object
- Presses spacebar when the object moves up
- Displays live video feed and mask

## Requirements
- Python 3.x  
- OpenCV  
- NumPy  
- PyAutoGUI  

## Demo Overview
To demonstrate the project in action:
I opened Pinterest in a web browser and used a yellow paper as a control object.
By moving the yellow paper up and down in front of the webcam, the script detects the movement and automatically scrolls the page (simulating a spacebar press).

Install dependencies with:
```bash
pip install opencv-python numpy pyautogui
