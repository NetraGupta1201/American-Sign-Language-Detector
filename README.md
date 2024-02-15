# American Sign Language Detector
[![Python](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/) 
[![Computer Vision](https://img.shields.io/badge/Computer%20Vision-cvzone%20%7C%20opencv-white?style=for-the-badge&logo=opencv&labelColor=black&color=darkgreen)](https://opencv.org/)

This project is an American Sign Language (ASL) detector implemented in Python, utilizing machine learning techniques. It is compatible with Python version 3.10 and above.

## Features

- Detects American Sign Language (ASL) gestures in real-time.
- Automatically installs necessary modules upon first run (Windows only).
- Utilizes OpenCV, MediaPipe, and scikit-learn libraries for image processing and machine learning.
- Trained model provided for immediate use or can be customized with additional symbols.

## Dependencies

Windows systems will support automatic installation of necessary modules.
Please refer to requirements.txt for requirements for different OS or download the following Python packages:
- `pickle`
- `opencv-python`
- `cvzone`
- `mediapipe`
- `sklearn`

## Installation

1. Clone or download the project repository to your local machine.

2. Navigate to the project directory.

3. Run the script `main.py`.

    ```
    python main.py
    ```

    - The script will automatically start the installation of necessary modules if they are not already installed. This is applicable only for Windows machines and may require admin access.

## Usage

- The ASL detector script automatically detects signs based on the inputs already stored in the `trained_model.p` file if it exists.

- Note that the ASL script needs to be trained if the model doesn’t exist. The GitHub repository has an uploaded model with letters A, B, C stored and trained, thus it is recommended to use that.

- If you want to make your own trained symbol file, follow these steps:
    1. Modify and run the `data_collection.py` file to collect data.
    2. Run `data_creation.py` to create the necessary data.
    3. Finally, train the model using `data_trainer.py`.

## Notes

- Some modules require installation, which could be restricted on networked computers. Ensure you have admin access to install these modules.

- This project is primarily designed to run on Windows machines.

- For further customization or troubleshooting, refer to the source code and comments within the project files.
