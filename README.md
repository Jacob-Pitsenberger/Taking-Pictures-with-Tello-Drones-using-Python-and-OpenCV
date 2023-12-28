# Taking Pictures with Tello Drones using Python and OpenCV

## Author
Jacob Pitsenberger

December 28, 2023

## Overview
This Python module demonstrates how to use OpenCV with the Tello EDU mini drone to stream video from its camera and save individual frames as PNG files when the 'p' key is pressed.

## Project Structure
- **take_pictures.py**: The main Python script containing the code for connecting to the Tello drone, streaming video, and capturing images.
- **pictures/**: The directory where captured images are saved.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- DJITelloPy (`djitellopy`)
- NumPy (`numpy`)

## Usage
1. Install the required dependencies:

   ```bash
   pip install opencv-python djitellopy numpy
   ```
   
2. Connect to the Tello drone and run the script:
    ```bash
    python take_pictures.py
    ```
   
    Use the 'p' key to capture images during the drone's video stream.

## Important Notes
Ensure that the Tello drone is connected to the computer's Wi-Fi network.
Press 'q' to exit the video stream.
Captured images will be saved in the pictures/ directory.

## License
This project is licensed under the [MIT License](license.txt).
