Eye-Controlled Mouse Cursor
This Python project leverages OpenCV, MediaPipe, and PyAutoGUI to create a system that controls the mouse cursor using eye movements. It captures video from a webcam, detects facial and eye landmarks, and translates these movements into screen coordinates for real-time interaction.

Features:
Real-time Eye Tracking: Uses MediaPipe's Face Mesh solution to detect and track eye movements in real-time.
Mouse Control: Maps the detected eye positions to screen coordinates, allowing the user to control the mouse cursor with their gaze.
Click Detection: Implements a blink detection mechanism to simulate mouse clicks, enabling hands-free interaction with the computer.
Customizable Sensitivity: Includes a scale factor to adjust the sensitivity of the cursor movement based on eye movements.
Cross-Platform Compatibility: Works on various operating systems including Windows, macOS, and Linux.
Dependencies:
OpenCV
MediaPipe
PyAutoGUI
NumPy
