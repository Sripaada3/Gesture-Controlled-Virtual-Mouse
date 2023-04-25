# Gesture-Controlled-Virtual-Mouse
Gesture Controlled Virtual Mouse using MediaPipe and OpenCV
This project demonstrates how to control the mouse pointer of a computer using hand gestures. It uses MediaPipe and OpenCV libraries for hand detection and tracking.

Requirements
To run this project, you will need:

Python 3.7 or higher
pyttsx3==2.71
SpeechRecognition==3.8.1
pynput==1.7.3
pyautogui==0.9.53
wikipedia==1.4.0
opencv-python==4.5.3.56
mediapipe==0.8.6.2
comtypes==1.1.11
pycaw==20181226
screen-brightness-control==0.9.0
eel==0.14.0
You can install these requirements using the following command:

bash
Copy code
pip install -r requirements.txt
Installation
Clone this repository to your local machine.
bash
Copy code
git clone https://github.com/<your-username>/gesture-controlled-virtual-mouse.git
Install the required Python libraries.
bash
Copy code
pip install -r requirements.txt
Usage
Run the Gesture_Controller.py file.
bash
Copy code
python Gesture_Controller.py
The camera will start, and you will see your hand on the screen. Make sure your hand is well-lit and in front of the camera.

Use the following gestures to control the mouse pointer:

Hold up your index finger to move the mouse pointer.
Hold up your index finger and your thumb to click the left mouse button.
Hold up your middle finger and your thumb to click the right mouse button.
To quit the program, press q.
