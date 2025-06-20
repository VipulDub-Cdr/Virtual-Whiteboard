## Virtual Painter with Finger Tracking

This project is a gesture-based virtual whiteboard developed using OpenCV, MediaPipe, and Python. It enables users to draw on a digital canvas using only hand gestures, without any physical contact.

The system captures real-time video from a webcam and uses MediaPipe’s hand tracking solution to detect hand landmarks. The index finger's tip is used as a drawing pointer. When the user raises one or more fingers, drawing begins. When all fingers are closed (fist gesture), drawing stops. A live feed shows the hand with landmarks, and a separate canvas displays the drawing.

Key features include:

    Real-time hand landmark detection

    Gesture recognition to control drawing state

    Smooth and continuous drawing using fingertip tracking