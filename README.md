# Drowsiness Detection

This project aims to detect driver drowsiness in real-time using computer vision techniques. The system alerts the driver when signs of drowsiness are detected to prevent potential accidents.

## Features

- **Real-time Detection**: Utilizes a webcam to monitor the driver's facial features continuously.
- **Eye Aspect Ratio (EAR)**: Calculates the EAR to determine if the driver's eyes are closed.
- **Drowsiness Alert**: Triggers an alarm if the eyes remain closed beyond a predefined threshold.

## Requirements

- Python 3.x
- OpenCV
- Dlib
- Imutils
- Scipy
- Pygame

Install the required packages using:

```bash
pip install -r requirements.txt


**## 1. Clone the repository:**
- git clone https://github.com/TeamWork28/Drowsiness.git

**## 2. Navigate to the project directory:**
- cd Drowsiness

**## 3. Run the drowsiness detection script:**
- python drowsiness_detect.py

**## How It Works**
- The system uses Dlib's facial landmark detector to identify the eye regions in the driver's face. By calculating the Eye Aspect Ratio (EAR), it determines whether the eyes are closed. If the eyes remain closed for a specified duration, an alarm is sounded to alert the driver.

**## Acknowledgments**
- The Eye Aspect Ratio (EAR) concept is based on research by Tereza Soukupova and Jan Cech in their paper "Real-Time Eye Blink Detection using Facial Landmarks."
