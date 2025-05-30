# Face Detector using OpenCV

## Overview
A simple face detection project using OpenCV's Haar Cascade classifier to detect faces in images and live webcam feed.

## Features
- Real-time face detection via webcam.
- Detection on static images.
- Lightweight and easy to use.

## Installation
   1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/facedetect.git
   2. Navigate to the project directory:
   ```bash
   cd facedetect
   3. Install dependencies:
   ```bash
   pip install -r requirements.txt
##Usage
   1.To detect faces in an image:
   ```bash
   python face_detector.py --image path/to/image.jpg
   2.To use your webcam for real-time face detection:
   ```bash
   python face_detector.py --webcam
   Make sure the haarcascade_frontalface_default.xml file is present in the same directory as your script.
##Project Structure
```bash
facedetect/
│
├── face_detector.py                   # Main script
├── haarcascade_frontalface_default.xml  # Haar Cascade model
├── requirements.txt                   # Python dependencies
└── README.md                          # Project documentation
##Contributing
Contributions are welcome! Feel free to fork the repository, open an issue, or submit a pull request.

##License
This project is licensed under the MIT License. See the LICENSE file for more details.



