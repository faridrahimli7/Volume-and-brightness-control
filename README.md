This project uses hand gestures to control screen brightness and system volume on a Windows PC. The program detects hand movements using a webcam, interprets them as commands, and adjusts the system settings accordingly.

The project leverages OpenCV and MediaPipe for hand tracking, while pycaw and screen_brightness_control libraries manage volume and brightness adjustments. The left hand controls screen brightness, and the right hand controls system volume.

Features
Brightness Control: Controlled by the distance between the thumb and index finger of the left hand.
Volume Control: Adjusted based on the distance between the thumb and index finger of the right hand.

How It Works:
  Hand Detection: Uses MediaPipe Hands to detect landmarks on each hand.
  Gesture Recognition:
    Left Hand: Distance between thumb and index finger adjusts brightness.
    Right Hand: Distance between thumb and index finger adjusts system volume.
  Control Mapping:
    Brightness and volume levels are mapped to the distance between detected hand landmarks.
