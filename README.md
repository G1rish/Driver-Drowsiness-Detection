Driver Drowsiness Detection & Alert System:

#Project Overview:

      This Python program monitors drowsiness in real-time using a webcam feed. It calculates the eye aspect ratio (EAR) to assess eye openness and triggers an alert if drowsiness is detected.

#Dependencies:

      scipy, imutils, dlib, opencv-python, and pygame.

#Functionality:

      Detects facial landmarks with dlib.
      Calculates the eye aspect ratio (EAR) to assess eye openness.
      Triggers an alert and plays a sound if EAR falls below a threshold for a certain number of frames (frame_check).
      Displays the real-time video feed.
      Press 'q' to exit.

#Instructions:

      Install dependencies with pip install.
      Ensure a facial landmarks model (shape_predictor_68_face_landmarks.dat) is in the "models" directory.
      The program captures video from the default webcam (cv2.VideoCapture(0)).
