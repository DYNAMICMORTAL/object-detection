# Object-Detection

[![Python Version](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/downloads/release/python-370/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<!--![Car Counter Demo](demo.gif)-->

## Overview

This repository contains a simple Python project for counting the number of cars in a video using object detection techniques. The project uses the OpenCV library for video processing and object detection. It utilizes background subtraction and contour analysis to detect and count vehicles passing through a specified line in the video.

## Requirements

- Python 3.10
- OpenCV (cv2) library
- NumPy

## Installation

1. Ensure you have Python 3.7 installed. If not, you can download it from the [official Python website](https://www.python.org/downloads/release/python-310/).

2. Clone this repository to your local machine:
   `https://github.com/DYNAMICMORTAL/object-detection.git`
3. Change into the project directory: `cd object-detection-car-counter`
4. Install the required dependencies: `pip install -r requirements.txt`


## Usage

1. Place the video file containing the cars to be detected in the `testVideos` directory.

2. Update the `carsVideo.mp4` file path in the `cap = cv2.VideoCapture('testVideos/carsVideo.mp4')` line of the `car_counter.py` file with the correct file name.

3. Run the car counter script: `python car_counter.py`

The script will process the video, detect cars, and display the video with bounding boxes around the detected vehicles. The count of cars crossing the specified line will be shown on the video.

4. Press `Enter` or `Return` to exit the video window.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contribution

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.



