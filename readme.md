# Push-Ups Counter

### Overview

This repository contains a Python script that counts the number of push-ups performed using a webcam or video file. The script uses the MediaPipe library for pose detection and calculates the angle between the shoulder, elbow, and hip to determine the push-up motion.

### Dependencies

- **Python 3.x**
- **numpy**
- **mediapipe**
- **opencv-python**

### Installation

1. **Install Python 3.x:** Ensure that Python 3.x is installed on your system.
2. **Install Required Libraries:** Run the following command to install the necessary Python libraries:
    ```bash
    pip install numpy mediapipe opencv-python
    ```
3. **Clone the Repository:** Download or clone this repository to your local machine.

## Usage

1. **Set VideoPath**:
   - Modify the `File_path` variable to match the name of your video file.

2. **Run the Script**:
    ```bash
    python pushups_counter.py
    ```

3. **Real-Time Push-Up Counting**:
   - The script will process the video and count the number of push-ups performed, displaying the count on the video feed.

4. Press 'q' to exit the video feed.

### Disclaimer

"This push-up counter is intended for personal use and may not be perfectly accurate for all body types and environments. The accuracy of the count can vary depending on the video quality, camera angle, and lighting conditions."
