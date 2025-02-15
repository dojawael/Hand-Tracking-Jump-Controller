# Hand Tracking Jump Controller 🖐🎮

####Overview:
This project is a hand-tracking-based jump controller that allows users to control actions (such as jumping) using hand gestures via a webcam. It utilizes OpenCV, cvzone's HandTrackingModule, and ctypes for keyboard input simulation.

####Features ✨:

* Real-time hand tracking using OpenCV and cvzone.

* Gesture recognition to detect the number of fingers up.

* Keyboard input simulation to trigger the space key for jumping.

* Mirrored camera correction to ensure accurate hand representation.

#### Dependencies 📦🔗:

* Ensure you have the following libraries installed:

```python
pip install opencv-python cvzone numpy
```

#### How It Works ⚙️:

* The program captures video from the webcam.

* It detects a single hand using HandDetector.

* Based on the number of fingers shown, different actions occur:

   - 0 fingers → Jump (press space key)

    - 1-5 fingers → No jump




#### Controls🖱️:

* Show 0 fingers → Press space (jump)

* Show 1-5 fingers → No action

* Press 'q' to quit.

#### Code Structure 🧑‍💻📂:

```main.py```: Contains the OpenCV-based hand-tracking logic.

```directkeys.py```: Defines PressKey() and ReleaseKey() for simulating key presses.

Enjoy coding! 🚀


