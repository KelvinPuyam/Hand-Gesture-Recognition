# Hand-Gesture-Recognition

Hand Gesture Recognition is a significant area of research in Human-Computer Interaction (HCI) technology. This project demonstrates the development of a real-time Hand Gesture Recognizer using the MediaPipe framework, TensorFlow, and OpenCV in Python.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Gesture recognition plays a crucial role in various applications such as virtual environment control, sign language translation, robot control, and music creation. This project utilizes MediaPipe, an open-source framework developed by Google, for hand detection and keypoint estimation. TensorFlow is employed for building and deploying a pre-trained gesture recognition model. OpenCV facilitates real-time image processing and webcam interaction.

## Prerequisites

Before running the project, ensure you have the following installed:
1. Python 3.x
2. OpenCV 4.5
3. MediaPipe 0.8.5
4. TensorFlow 2.5.0
5. NumPy 1.19.3

## Installation

Create a new virtual environment with Python version 3 or higher installed. You can install the required packages using pip:
```bash
pip install -r requirements.txt
```
This ensures that you have a clean environment with the necessary dependencies installed to run the project.

## Usage

1. Clone this repository to your local machine and in your terminal, go to the project directory.
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

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve this project.

## License

This project is licensed under the [MIT License](https://github.com/KelvinPuyam/Hand-Gesture-Recognition/blob/main/LICENSE).
