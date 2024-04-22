# Hand-Gesture-Recognition

Hand Gesture Recognition is a significant area of research in Human-Computer Interaction (HCI) technology. This project demonstrates the development of a real-time Hand Gesture Recognizer using the MediaPipe framework, TensorFlow, and OpenCV in Python.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the Python script](#running-the-python-script)
- [Running the Flask Web Application](#running-the-flask-web-application)
- [Accessing the Application](#accessing-the-application)
- [Contributing Guidelines](#contributing-guidelines)
- [License](#license)

## Introduction

Gesture recognition plays a crucial role in various applications such as virtual environment control, sign language translation, robot control, and music creation. This project utilizes MediaPipe, an open-source framework developed by Google, for hand detection and keypoint estimation. TensorFlow is employed for building and deploying a pre-trained gesture recognition model. OpenCV facilitates real-time image processing and webcam interaction.

## Prerequisites

Before running the project, ensure you have the following installed:
1. Python 3.x
2. OpenCV 4.5
3. MediaPipe 0.8.11
4. TensorFlow 2.5.0
5. NumPy 1.19.3

## Installation

Create a new virtual environment with Python version 3 or higher installed. You can install the required packages using pip:
```bash
pip install -r requirements.txt
```
This ensures that you have a clean environment with the necessary dependencies installed to run the project.

## Running the Python script

1. Clone this repository to your local machine and go to the project directory.
```bash
git clone https://github.com/KelvinPuyam/Hand-Gesture-Recognition.git
```
```bash
cd Hand-Gesture-Recognition
```
2. Install the prerequisites as mentioned above.
```bash
pip install -r requirements.txt
```
3. Run the Python script.
```bash
python hand_gesture_detection.py
```
4. Ensure your webcam is connected and functional.
5. Perform hand gestures in front of the webcam to observe real-time recognition.

## Running the Flask Web Application

After cloning the repository and navigating to the project directory, ensure you have installed the required dependencies.

Run the Flask web application using the following command:

```bash
python app.py
```

When you run `app.py`, the Flask web application initializes the hand gesture detection system using MediaPipe, TensorFlow, and OpenCV. It starts a server listening on [http://127.0.0.1:5000](http://127.0.0.1:5000).

## Accessing the Application

Ensure your webcam is connected and functional.

Open a web browser and go to [http://127.0.0.1:5000](http://127.0.0.1:5000).

Upon accessing the provided URL, the web application interface for hand gesture detection will be displayed. You can perform hand gestures in front of the webcam to observe real-time recognition.

## Contributing Guidelines

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

## License

This project is licensed under the [MIT License](https://github.com/KelvinPuyam/Hand-Gesture-Recognition/blob/main/LICENSE).
