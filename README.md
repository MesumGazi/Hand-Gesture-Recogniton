# Hand-Gesture-Recogniton
This project is a hand gesture recognition system that can recognize three hand gestures: "Hello", "Goodbye", and "Peace". It uses OpenCV to capture and process video from a webcam, and Keras to classify hand gesture images.

Requirements

Python 3.x
OpenCV
cvzone
Keras


Installation

Clone the repository to your local machine
Install the required dependencies using pip: pip install opencv-python cvzone keras
Usage
Run the script: python hand_gesture_recognition.py
Hold your hand up to the webcam and make one of the three gestures ("Hello", "Goodbye", or "Peace")
The program will classify the gesture and display the result on the screen


Notes
This program uses a pre-trained Keras model to classify hand gestures. If you want to train your own model, you can modify the keras_model.h5 file or train a new model from scratch.
The program is currently set up to recognize gestures from one hand only. If you want to recognize gestures from both hands, you will need to modify the code.
This project was created as part of a tutorial on OpenCV and Keras. You can find the tutorial on my blog.


Credits


The cvzone library was used to simplify hand detection and cropping. You can find the library on GitHub.
The Keras model used in this project was trained on the training machine website from Google.


License


This project is licensed under the MIT License. See the LICENSE file for more details.

Contact
For questions or support, please contact [Gazi Meesam] at [gazi.xyzx@gmail.com].
