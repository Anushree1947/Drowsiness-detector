# Drowsiness Alert: Smart Eye Monitoring System

A real-time driver drowsiness detection app built with Python, OpenCV and Dlib. 
It watches the driver through a webcam and sounds an alarm when the eyes stay closed.

## Demo
Live webcam tests I ran myself:

![[Caption: e.g. Eyes open, status Alert]](https://github.com/user-attachments/assets/41f138e8-7191-427f-8a5c-07bd5737cc49)
![[Caption]](https://github.com/user-attachments/assets/dab9b8cf-2d77-488f-9a2a-2c5c0371312f)
![[Caption]](https://github.com/user-attachments/assets/8ef961be-370f-4d3d-a392-a33a2c3242da)
![[Caption]](https://github.com/user-attachments/assets/500a9ed3-2022-4103-b4e5-288b6acec5bd)
![[Caption: e.g. Eyes closed, alarm triggered]](https://github.com/user-attachments/assets/15c8230c-7b44-4f92-b740-eb1e476ba9dd)

## How it works
1. Capture video from the webcam with OpenCV
2. Detect the face and facial landmarks with Dlib
3. Calculate the Eye Aspect Ratio (EAR) for both eyes
4. [Confirm: also track mouth movement to detect yawning]
5. If EAR stays below [threshold value] for [N] consecutive frames, play the alarm

## Tech stack
Python, OpenCV, Dlib, NumPy, imutils, Jupyter Notebook

## Results
- Tested live on [number] sessions, with [conditions: lighting, glasses, etc.]
- [What happened, e.g. "alarm triggered correctly in X of Y eye-closure tests"]
- [Anything it missed or got wrong]

## How to run
1. Clone this repo
2. Install: `pip install opencv-python dlib numpy imutils`
3. Open [notebook file name] in Jupyter and run all cells
4. Press [key] to quit

Tested on: Windows 11, Intel Core i3, 8 GB RAM, built-in webcam.

## My role
[What you built yourself. If this was a group project, say what teammates did.]

## Limitations and next steps
[e.g. needs good lighting, one face at a time, glasses may affect results]
Result : These are the Pictures Live Captured Down Below, Which is tried and tested By me. 







