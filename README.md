#  Hand Tracking with Mediapipe


[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

This Python project utilizes the Mediapipe library to track hand landmarks in real-time from the webcam feed. It provides an interactive interface to visualize the hand landmarks and displays a highlighted circle around the tip of the index finger for better visibility.

![Demo](demo.gif)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [MyProject](#MyProject)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Hand Distance Measurement project uses Google's Mediapipe library to accurately detect hand landmarks and compute the distance between the tip of the thumb and the tip of the index finger. The distance is then converted into centimeters using a pre-calibrated polynomial regression model. The application provides a user-friendly interface to visualize the hand landmarks and the computed distance in real-time, making it useful for various applications, including interactive virtual environments and gesture-based control systems.

## Features

- Real-time hand landmark detection using Mediapipe.
- Visualization of hand landmarks and bounding box on the video stream.
- Highlighting the tip of the index finger with a circle for easy identification.
## My Project
 This is a description of my awesome project!

 
 <img
  src="one_hand_1.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

  <img
  src="two_hand.png"
  alt="Alt text"
  title="Optional title"
  style="display: inline-block; margin: 0 auto; max-width: 300px">

## Installation

1. Clone the repository to your local machine:
2. Install the required packages using pip:
 - Python 3.x
 - OpenCV (`pip install opencv-python`)
 - Mediapipe (`pip install mediapipe`)
## Usage

1. A window will open displaying the webcam feed with real-time hand landmark tracking. The script will highlight the tip of the index finger with a yellow circle for better visibility.
2. To exit the application, press the 'q' key.

## Contributing

Contributions are welcome! If you have any ideas, bug fixes, or improvements, please feel free to submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE). You can freely use and modify the code, subject to the terms of the license agreement.

