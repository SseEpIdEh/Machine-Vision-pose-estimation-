# Machine-Vision-pose-estimation-
Pose Estimation in Machine Vision

This repository contains a Python script that performs pose estimation using OpenCV and the Mediapipe library. The script reads frames from a video file and applies pose estimation algorithms to detect and visualize human poses.

Installation
To run the code in this repository, you need to have the following dependencies installed:

Python 3
OpenCV
Mediapipe
NumPy
You can install the necessary dependencies using the following command:

To use the code in this repository, follow these steps:


***Make sure you have a video file in the specified path (C:/Users/Mehrdad/PycharmProjects/Files and codes/clips/4.mp4). If you have a different video file, update the path accordingly in the code.**

**The script will process each frame of the video, perform pose estimation, and display the results in two windows: "Pose" and "Blank".
The "Pose" window shows the original frame with overlaid pose landmarks and connections.
The "Blank" window displays a blank canvas where detected poses and their shapes are visualized.
Press any key to exit the script.**
......Description
**The provided script performs pose estimation using the Mediapipe library and OpenCV. It detects human poses in each frame of the video and applies different shape recognition algorithms. Currently, it recognizes two shapes: "T" and "Y".
For the "T" shape recognition, the script checks the relative positions of specific pose landmarks and draws blue lines connecting them. If the conditions for the "T" shape are met, the "T" shape is displayed on both the original frame and the blank canvas.
For the "Y" shape recognition, the script checks the relative positions of specific pose landmarks and draws blue lines connecting them. If the conditions for the "Y" shape are met, the "Y" shape is displayed on the blank canvas.
Please note that this script is a basic implementation and can be further customized or extended based on your requirements.**

Contributions
Contributions to this repository are welcome. If you have any improvements, bug fixes, or additional functionality to add, please feel free to create a pull request.
