# <h1 align="center">🚗 Car Parking Space Detection System 🚗</h1>
<p align="center">
  <img src="img.png" alt="Parking Lot Detection" width="500"/>
</p>

## 🔍 Overview
Welcome to the Car Parking Space Detection System! This project harnesses the power of OpenCV and Python to automatically detect free and occupied parking spaces in a video feed. By analyzing each frame, the system marks free spaces with green rectangles and occupied ones with red. Real-time updates show the number of available parking spaces, making it perfect for smart parking solutions!

## 🌟 Features
* Real-Time Parking Monitoring: Instantly identifies free and occupied parking spaces in a given video.
* Dynamic Updates: Displays live updates on the number of free spaces available at all times.
* Customizable Detection Areas: Easily adjust the detection area (rectangle size) for different parking space dimensions.
* Color-Coded Visuals: Free spaces are highlighted in green and occupied spaces in red for easy identification.
* Efficient Processing: Uses advanced computer vision techniques like adaptive thresholding for accurate space detection.
## ⚙️ Requirements
To run this system, you will need:

* Python 3.x
* OpenCV for handling computer vision tasks
* NumPy for array and numerical operations
* Pickle for saving and loading parking space positions
## 💡 How It Works
* Video Feed Processing: The system processes a video file of a parking lot, analyzing each frame for parking space status.
* Image Preprocessing: It converts frames to grayscale, applies blurring, and uses adaptive thresholding for better space detection.
* Parking Space Detection: The system checks each parking spot to see if it's occupied or free based on pixel counts and applies appropriate markings (rectangles).
* Real-Time Count: Displays an updated count of available parking spaces as the video plays.
## 🚀 How to Use
1. Clone the Repository
Clone or download the repository to your local machine to get started.

2. Place the Video
Ensure the carPark.mp4 video file is placed in the same directory as the project.

4. Run the Script
Execute the script to begin detecting available parking spaces in the video.

5. View the Output
The parking lot video will display color-coded rectangles indicating free and occupied spaces, along with the count of free spaces.

## 🎯 Future Enhancements
Live Camera Integration: Expand the system to work with live camera feeds for real-time parking monitoring.
User Notifications: Implement alerts to notify users when free parking spaces are available.
Machine Learning Integration: Enhance detection accuracy using machine learning models to adapt to different environments and lighting conditions.
