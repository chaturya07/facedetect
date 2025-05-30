# Face Detector using OpenCV

## Overview
A simple face detection project using OpenCV's Haar Cascade classifier to detect faces in images and live webcam feed.

## Features
- Real-time face detection via webcam.
- Detection on static images.
- Lightweight and beginner-friendly.
- Easy to extend for advanced computer vision applications.

## Requirements
- Python 3.x
- pip
- OpenCV
- NumPy

You can install all required packages with the provided `requirements.txt` file.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/facedetect.git
   ```

2. Navigate to the project directory:
   ```bash
   cd facedetect
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. To detect faces in a static image:
   ```bash
   python face_detector.py --image path/to/image.jpg
   ```

2. To detect faces in real-time using your webcam:
   ```bash
   python face_detector.py --webcam
   ```

Note: Make sure the file `haarcascade_frontalface_default.xml` is in the same folder as your `face_detector.py` script.

## Contributing
Contributions are welcome. If you'd like to improve this project, feel free to fork the repository and submit a pull request. Please open an issue first to discuss your proposed changes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
