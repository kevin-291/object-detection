# Real-Time Object Detection App using YOLOv9

This repository contains a Python script for a real-time object detection application using the YOLOv9 model from Ultralytics. The application uses the default camera (webcam) for video input and displays detected objects with bounding boxes, including labels of the detected object and their probability.

## Features

- Real-time object detection using YOLOv9.
- Draws bounding boxes around detected objects with class labels and confidence scores.
- Uses OpenCV for video capture and display.

## Prerequisites

- Python 3.7 or later
- A working webcam or video capture device

## Installation

1. Clone this repository:

    ```shell
    https://github.com/kevin-291/object-detection.git
    cd object-detection
    ```

2. Create a Python virtual environment (optional but recommended):

    ```shell
    python3 -m venv venv
    source venv/bin/activate  # For Unix/Linux
    # OR
    venv\Scripts\activate  # For Windows
    ```

3. Install the required Python packages:

    ```shell
    pip install -r requirements.txt
    ```

## Usage

1. Run the script:

    ```shell
    python app.py
    ```

2. The app will open a video stream from the default camera and start detecting objects in real-time.

3. Press `q` on the keyboard to exit the application.

## Notes

- If you want to change the video input source, modify the argument to `cv2.VideoCapture()` in the script.

## License

This project is licensed under the MIT License.

## Credits

- [Ultralytics YOLOv9](https://github.com/ultralytics/assets/releases/download/v8.2.0/yolov9c.pt) for the object detection model.
- [OpenCV](https://github.com/opencv/opencv) for video processing and display.

