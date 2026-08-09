# Face Recognition System

## Description

The Face Recognition System is a simple Python project that uses a webcam to detect and recognize faces. I developed this project to understand how face detection and recognition work in real time using OpenCV.

The system first captures face images through the webcam and stores them as a dataset. These images are then used to train the recognition model. After training, the system can recognize a registered person when they appear in front of the camera. If the face is not registered, it displays the person as **Unknown**.

This project helped me learn about computer vision, image processing, face detection, and real-time camera applications using Python. It can also be further developed for applications such as student attendance, employee identification, and basic security systems.

## Technologies Used

* Python 3.13
* OpenCV
* NumPy
* VS Code
* Webcam

## Main Features

* Detects faces using a webcam
* Captures face images for registration
* Trains the face recognition model
* Recognizes registered people
* Displays the person's name
* Shows unknown faces separately

## How It Works

The project follows these basic steps:

1. The webcam captures the person's face.
2. The system detects the face from the camera frame.
3. Face images are collected and stored.
4. The collected images are used to train the model.
5. The trained model compares new faces with the stored faces.

## Purpose of the Project

The main purpose of this project is to learn how face recognition technology works and how it can be implemented using Python and OpenCV. It is mainly developed as an educational project and can be improved with additional features in the future.

## Future Improvements

In the future, this project can be extended by adding an attendance system, database connectivity, a graphical user interface, and better recognition accuracy.

## Development Environment

**Language:** Python 3.13
**Editor:** Visual Studio Code
**Library:** OpenCV
