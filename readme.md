# Real-Time Color Detection using OpenCV

This Python script captures video from the default camera and performs real-time color detection on the central pixel of each frame using OpenCV. The detected color is then labeled and displayed on the frame. This can be useful for various applications such as object tracking, color-based segmentation, and more.

## Prerequisites

- Python 3.x
- OpenCV (cv2) library

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nightwing02/color-detection.git
   ```

2. Install the required dependencies:

   ```bash
   pip install opencv-python
   ```

## Usage

1. Navigate to the project directory:

   ```bash
   cd real-time-color-detection
   ```

2. Run the script:

   ```bash
   python color_detection.py
   ```

3. Press the 'Esc' key to exit the application.

## How it Works

- The script sets up a video capture object from the default camera.
- It continuously reads frames from the camera.
- For each frame, it converts the color space from BGR to HSV.
- It determines the central pixel's HSV value and extracts its hue component.
- Based on the hue value, it categorizes the color into predefined ranges.
- The detected color is then labeled and displayed on the frame.
- Press the 'Esc' key to exit the application.

## Customization

- You can adjust the color ranges and classifications based on your requirements by modifying the code.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This project was inspired by the need for real-time color detection in computer vision applications.

---
