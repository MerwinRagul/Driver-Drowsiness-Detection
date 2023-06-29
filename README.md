# Driver-Drowsiness-Detection
Drowsiness Detection OpenCV
This code can detect your eyes and alert when the user is drowsy.

Applications
This can be used by riders who tend to drive for a longer period of time that may lead to accidents.

Algorithm
Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:.


Condition
It checks 20 consecutive frames and if the Eye Aspect ratio is lesst than 0.25, Alert is generated.

LIBRARIES HAVE TO IMPORT:
import imutils
import dlib
import cv2

