# Pose Estimator

This is a project that uses OpenCV and Mediapipe to estimate human poses from images or videos. The pose estimator can detect 33 landmarks on the human body, such as the eyes, ears, nose, shoulders, elbows, wrists, hips, knees and ankles. The pose estimator can also calculate the angles between the limbs and display them on the output.

## Requirements

- Python 3.6 or higher
- OpenCV
- Mediapipe
- Numpy

## Usage

- Clone this repository or download the files.
- Import the `PoseModule.py` file in your Python script or notebook.
- Create an object of the `poseDetector` class and pass the desired parameters, such as `mode`, `upBody`, `smooth`, `detectionCon` and `trackCon`.
- Use the `findPose` method to detect the pose from an image or a video frame and return the output image with the landmarks and angles drawn on it.
- Use the `findPosition` method to get the coordinates and ids of the landmarks from an image or a video frame.
- Use the `findAngle` method to get the angle between three landmarks from an image or a video frame.
### Featuring 2 regular exercises
#### Push-ups
- Execute the file `pushup.py`.
- A counter is initialized at the bottom left of the window, it keeps track of the correct pushup.
#### Squats
- Execute the file `Squats.py`.
- A counter is initialized at the bottom left of the window, it keeps track of the correct squat.

## Acknowledgements

This project is inspired by the following resources:

- https://google.github.io/mediapipe/solutions/pose.html
- https://www.youtube.com/watch?v=brwgBf6VB0I
