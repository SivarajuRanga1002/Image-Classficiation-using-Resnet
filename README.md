# Object Detection Module for Robotics

This repository contains the `object_detector.py` script, a key component of a robotic vision system designed to detect and analyze objects based on color within a simulated environment using ROS (Robot Operating System). This module is part of a larger project aimed at implementing a sophisticated object manipulation and recognition system for automated tasks.

## Project Overview

The `object_detector.py` script utilizes OpenCV and ROS to detect objects within a camera's field of view in a Gazebo simulation environment. The script identifies objects by their color signatures and calculates their positions, dimensions, and the estimated depth from the camera lens.

## Key Features

- **Color-based Object Detection**: Utilizes HSV color space to differentiate objects based on predefined color ranges.
- **3D Position Estimation**: Combines depth sensing and camera calibration to compute the 3D coordinates of detected objects relative to the camera.
- **ROS Integration**: Fully integrated with ROS, allowing for easy deployment on robotic systems and simulation in environments like Gazebo.
- **Dynamic Object Tracking**: Capable of tracking multiple objects simultaneously and updating their positions in real-time.

## Technologies Used

- **ROS**: Robot Operating System provides libraries and tools to help software developers create robot applications.
- **OpenCV**: Open Source Computer Vision Library that extends its capabilities towards computer vision and machine learning.
- **Python**: The project is scripted in Python, leveraging its vast ecosystem of libraries for rapid development and prototyping.
- **Gazebo**: Simulation environment used to test and refine the detection algorithms in a controlled setting.

## Setup and Configuration

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
