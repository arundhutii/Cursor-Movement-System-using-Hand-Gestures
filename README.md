# README
## # Cursor-Movement-System-using-Hand-Gestures

This is a Python project for controlling a computer's mouse cursor using hand gestures. The program recognizes hand gestures through a webcam using the Mediapipe library and controls the mouse cursor via the PyAutoGUI library.

The project is divided into two files, `app.py` and `controller.py`. The `app.py` file contains the main program logic while `controller.py` is responsible for handling the mouse cursor movement and click events.

## Requirements
#### To run the program, the following libraries are required:<br>
  - OpenCV<br>
  - Mediapipe<br>
  - PyAutoGUI<br>
 
#### You can install these libraries using pip:<br>
  -  `pip install opencv-python mediapipe pyautogui`<br>

## How to Run
After installing the required libraries, run the `app.py` file in a Python environment with a webcam. The program will start capturing video from the webcam, and the mouse cursor can be controlled using the following hand gestures:

  - **Cursor moving**: Raise all fingers together and move your hand to move the cursor and control it.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Cursor freezing**: Close your thumb and Raise all other fingers together freeze the cursor and prevent it from moving.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Drag and drop**: Close your hand into a fist and move it around to drag and drop objects.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Right-click**: Raise your index finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Left-click**: Raise your middle finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Double-click**: Raise your index and middle finger while keeping the other fingers closed.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Scroll up**: Move your index and middle finger towards the screen.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Scroll down**: Move your index and middle finger away from the screen.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Zoom in**: Pinch your index finger and thumb together.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 
  - **Zoom out**: Spread your index finger and thumb apart.<br><br>
    &nbsp;&nbsp;&nbsp;&nbsp; 

## How it Works
The program uses the Mediapipe library to detect hand landmarks from the video captured by the webcam. The `controller.py` file contains the logic for mapping the hand landmarks to specific mouse cursor actions, such as movement and clicking.

## Limitations
The program currently only supports controlling a single mouse cursor, and it may not work well in low-light conditions. It also doesn't support handling gestures of more than one hand, however this is easy to overcome, may be in upcomming commits of this project.

