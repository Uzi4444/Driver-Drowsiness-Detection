Driver Drowsiness Detection-:sleeping::minibus::collision:
============

![made-with-python](https://img.shields.io/badge/made%20with-Python-blue.svg)
# Driver-Drowsiness-Detection
This system monitors drowsiness by detecting the driver's face and sending a drowsiness alert if his eyes have been closed for a certain number of frames. The user can configure their own threshold by specifying an EAR ratio and customising the number of frames if they do not want to use the defaults.
---

## Libraries used:
- `dlib` for the face detection model
- `opencv-python` for drawing frames around the eyes
- `tkinter` for the GUI
- `playsound` to play the alarm
- `scipy` for Euclidean distance calculations


---

**You must have Python 3.6 or higher to run the file.**
