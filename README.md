# Volume control system using gestures
In this project we are going to learn how to use Gesture Control to change the volume of a computer. 
We first look into hand tracking and then we will use the hand landmarks to find gesture of our hand to change the volume.

## Features
* Can change your computer's volume based on your hand activity
* Can track your hand in real-time

## How to use?
Step 1:
Clone this repository on your local computer

`git clone https://github.com/Nathan-Busse/Control-volume-with-gestures.git`

Step 2:
Install all the requirements

`pip install -r requirements.txt`

Note make sure you are giving the correct directory in the terminal.
The file is installed in your Local Disk direcetory.
e.g 'cd C:\Users\<User Name>\Control-volume-with-gestures'

Step 3:
Run the program

`python ctrl.py`

Note: You might have to wait for sometime usually 1-2 minutes for program to start and work properly.

## Video of output



## Special help
You might face issue with webcam not showing or something related to webcam.
To solve it just change the value/webcam from python files.

`cv2.VideoCapture(0)`

You can increment the number `0` until you see your webcam.

