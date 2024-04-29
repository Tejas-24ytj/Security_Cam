# Security Camera with Motion Detection using OpenCV

This project demonstrates how to set up a simple security camera system using OpenCV in Python. The system detects motion using a webcam and plays an alert sound when motion is detected.

## Requirements

- Python 3.x
- `opencv-python` library (`pip install opencv-python`)
- `winsound` library (Windows-specific, for playing alert sounds)

## Usage

1. Clone or download the repository to your local machine.

2. Install the required dependencies:

    ```bash
    pip install opencv-python
    ```

3. Run the `security_camera.py` script:

    ```bash
    python security_camera.py
    ```

4. The script will open a window displaying the webcam feed. When motion is detected, an alert sound will play.

5. Press 'q' to exit the program.

## How It Works

- The script captures video frames from the webcam using OpenCV's `VideoCapture` class.

- It then calculates the difference between consecutive frames to detect motion in the scene.

- When motion is detected, the script plays an alert sound using the `winsound` library.

## Configuration

- You can adjust parameters such as motion sensitivity, alert sound, and camera index in the `security_camera.py` script to customize the behavior of the security camera system.

## Notes

- Ensure that your environment has a webcam accessible to capture video frames.

- The accuracy and performance of the motion detection system may vary depending on factors such as lighting conditions, camera quality, and scene complexity.

- This project provides a basic implementation of a security camera system. For production-grade applications, consider additional features such as recording video footage, sending email alerts, or integrating with home automation systems.

## Credits

- This project was inspired by various tutorials, articles, and open-source projects related to motion detection and security camera systems.

## License

This project is licensed under the [MIT License](LICENSE).
