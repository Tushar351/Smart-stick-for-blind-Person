# Smart-stick-for-blind-Person

Installation
To run this program, you need to install the following dependencies:

Python 3.x

OpenCV

NumPy

gTTS

Pygame

This is a Python program that uses the OpenCV library for real-time face detection and a text-to-speech engine to generate audio cues for navigation based on the position of the detected face. The program runs indefinitely until the user presses the 'q' key to quit the program.

Here's a brief overview of what the code does:

1. Import necessary modules for image processing, audio conversion, and playing audio files using Python.
2. Load a pre-trained Haar cascade classifier for object detection.
3. Initialize the Pygame library.
4. Start capturing video from a camera.
5. Define a function to generate and play audio cues.
6. Define a function to navigate based on the position of the largest face in the frame.
7. In a loop, read a frame from the video stream and convert it to grayscale.
8. Detect faces in the grayscale frame using the loaded Haar cascade classifier.
9. Draw a rectangle around the detected faces in the frame.
10. Navigate according to the position of the largest face in the frame by generating and playing an appropriate audio cue.
11. Show the resulting frame with the detected faces and rectangles drawn around them.
12. Check if the user has pressed the 'q' key to quit the program.
13. Release the video capture and close all windows.

Overall, this code can be used for real-time face detection and navigation in a variety of applications, such as assistive technologies for people with visual impairments .
