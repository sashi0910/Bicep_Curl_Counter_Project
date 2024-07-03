# Bicep Curl Counter

# Table of Contents
1. Project Overview
2. Features
3. Installation
4. Usage
5. How It Works
6. Technologies Used
7. Future Enhancements
8. Contributing
9. License
10. Acknowledgements
11. Project Overview

The Bicep Curl Counter is an AI-powered application that uses computer vision to detect and count bicep curls in real time. Leveraging the capabilities of MediaPipe and OpenCV, this project provides an interactive way to monitor workout sessions and track the performance of bicep curls accurately.

## Features
- Real-Time Bicep Curl Detection: Continuously monitor and count bicep curls using live video feed.
- Angle Calculation: Calculates the angle between shoulder, elbow, and wrist to identify the stages of the curl.
- Visual Feedback: Provides real-time visual feedback with annotations on the video feed.
- Progress Tracking: Counts the number of curls performed and displays the count.
- User-Friendly Interface: Simple and easy-to-use interface for fitness enthusiasts and professionals.

## Usage Instructions:

- The application will open your default webcam.
- Perform bicep curls in front of the camera.
- The application will start counting curls automatically.
- Press q to exit the application.

## How It Works

- Pose Detection: The application uses MediaPipe’s Pose module to detect body landmarks.
- Angle Calculation: It calculates the angle at the elbow joint to determine the bicep curl position.
- Curl Counting Logic:
The counter increases when the angle between the shoulder, elbow, and wrist passes a certain threshold.
The stage changes based on the movement from full extension (down) to curl (up).
- Visual Feedback: Annotations are added to the live video feed to display angles and count.

## Technologies Used

1. Python: Core language for application development.
2. OpenCV: Used for video capture and image processing.
3. MediaPipe: Provides pose detection and landmark identification.
4. NumPy: For numerical operations and angle calculations.

## Future Enhancements

- Exercise Variety: Extend the application to detect and count other types of exercises.
- Performance Metrics: Add features to track exercise form and provide feedback.
- Mobile App Integration: Develop a mobile application version for ease of use.
- Database Integration: Store exercise data for long-term tracking and analytics.

## Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (`git checkout -b feature-branch`).
Commit your changes (`git commit -m 'Add new feature'`).
Push to the branch (`git push origin feature-branch`).
Create a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- MediaPipe: For providing an easy-to-use library for pose estimation.
- OpenCV: For the robust image processing tools.
- NumPy: For making numerical operations straightforward.
