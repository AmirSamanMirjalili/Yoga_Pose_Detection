# Yoga Pose and Human Detection Project

## Overview
This project encompasses two main components: human detection using YOLOv3 and performing the correct movement in yoga poses using MediaPipe and machine learning models. The goal is to accurately detect humans in images and videos and to analyze and correct yoga poses in real-time.

## Human Detection with YOLOv3
The human detection part of the project utilizes the YOLOv3 (You Only Look Once version 3) algorithm, a popular deep learning model known for its speed and accuracy in object detection tasks. This component is designed to identify and localize humans in both images and video streams.

### Key Features:
- Utilization of pre-trained YOLOv3 model for efficient human detection.
- Processing of images and real-time video streams to detect human presence.
- Application of computer vision techniques for image preprocessing and analysis.

## Performing the Correct Movement in Yoga
The yoga pose analysis component leverages the MediaPipe framework for pose estimation and TensorFlow for pose classification. It aims to guide users in performing yoga poses correctly by providing real-time feedback.

### Key Features:
- Real-time pose estimation using MediaPipe.
- Classification of yoga poses using a pre-trained model in TensorFlow.
- Calculation of angles between joints to analyze the correctness of poses.
- Real-time feedback to the user for correcting the pose.

## Technologies Used
- Python: The primary programming language used for implementing algorithms and processing data.
- OpenCV: Used for image and video processing tasks.
- TensorFlow: Utilized for loading and inferring from pre-trained deep learning models.
- MediaPipe: A framework for building multimodal applied machine learning pipelines, used here for pose estimation.
- YOLOv3: A state-of-the-art, real-time object detection system.

## Setup and Installation
1. Ensure Python 3.x is installed on your system.
2. Install necessary Python libraries using `pip install -r requirements.txt` .
3. Download the pre-trained YOLOv3 model weights and configuration files, and place them in the specified directory.
4. For the yoga pose analysis, ensure you have the TensorFlow model saved and accessible by the script.

## Running the Project
- For human detection, run the script designed for either image input or real-time video stream.
- For yoga pose analysis and correction, run the script that initializes the MediaPipe pose estimation and starts the webcam feed for real-time analysis.
- ![alt text]([images/example.png](https://github.com/AmirSamanMirjalili/Yoga_Pose_Detection/blob/master/result1.PNG))
- ![alt text]([images/example.png](https://github.com/AmirSamanMirjalili/Yoga_Pose_Detection/blob/master/result2.PNG))
## Conclusion
This project demonstrates the integration of advanced computer vision and deep learning techniques for practical applications such as human detection and real-time yoga pose correction. It showcases the power of combining different technologies to create an interactive and helpful tool for yoga practitioners.

## Future Work
- Enhance the yoga pose model to include more poses and improve accuracy.
- Implement a user-friendly interface for easier interaction with the yoga pose correction system.
- Explore optimization techniques for faster processing and real-time performance improvements.
