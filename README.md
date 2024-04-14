# Sleep-Detection
A sleep detection project for self-driving cars via Image Processing with AI.

This Python script, `sleep_detection.py`, is designed to monitor signs of drowsiness or sleep in individuals, particularly useful for drivers or individuals in critical monitoring jobs. Using real-time video data, the script detects indicators of sleepiness and can trigger alerts to prevent accidents or mishaps.

## Features

- Real-time sleepiness detection using facial landmarks.
- Alert system that triggers warnings when drowsiness is detected.
- Ability to process video input from various sources (webcams, recorded video, etc.).
- Adjustable sensitivity to accommodate different user thresholds for drowsiness indicators.

## Prerequisites

Before you run the script, ensure that you have the following installed:

- Python 3.x
- OpenCV: For image processing and facial landmark detection.
- Dlib: A toolkit for machine learning and facial landmark detection.
- Playsound: For playing alert sounds when drowsiness is detected.

You can install the required libraries using pip:

```bash
pip install opencv-python dlib playsound
```

## Installation
To get started with the sleep detection system, clone this repository:
```
git clone https://github.com/ranuelyn/Sleep-Detection.git
```
## Usage
To execute the sleep detection script, navigate to the directory where the script is located and run:
```bash
python sleep_detection.py
```
The script will start processing the video feed and monitor for signs of drowsiness in real-time.

## Libraries Used
- OpenCV: For image acquisition and processing tasks.
- Dlib: For facial feature detection and machine learning algorithms.
- Playsound: To play an alert sound when the system detects drowsiness.

## Contributing
If you would like to contribute to the development of this sleep detection system, please feel free to fork this repository, make your changes, and submit a pull request. Bug reports and feature suggestions can be submitted through the repository's Issues section.


