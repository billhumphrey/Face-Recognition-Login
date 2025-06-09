# Face-Recognition(Login)

This project implements a real-time face recognition login system using OpenCV and ONNX models.

  # Features:
Face detection using face_detection.onnx

Face recognition using face_recognition.onnx

Reference image preprocessing

Real-time webcam face matching

Login success triggered by L2 similarity threshold

   # How It Works:
Load and process a reference face image.

Start webcam and detect faces in real-time.

Compare each detected face to the reference using L2 distance.

If a face matches consistently, grant access.

  # Requirements:
Python 3.x

OpenCV with contrib modules

NumPy

Matplotlib

ONNX models (face_detection.onnx, face_recognition.onnx)

  # Usage:
Place your reference image in img/new/6.jpg.

Run the script.

Look into the webcam to log in.
