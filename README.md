# Virtual Paint Application

This project is a virtual paint application that allows users to draw on a canvas using hand gestures detected by a webcam. The application is built using Python, leveraging OpenCV for image processing, MediaPipe for hand tracking, and Numpy for numerical operations. The user can switch colors, clear the canvas, and draw in real-time using simple hand movements.

## Demo

![Air Canvas Demo](https://path-to-demo-image-or-gif)

## Features

- **Hand Tracking:** Uses MediaPipe to detect and track hand movements.
- **Gesture-Based Drawing:** Draw on a virtual canvas using your index finger.
- **Color Selection:** Switch between four colors (Blue, Green, Red, Yellow) using on-screen buttons.
- **Clear Canvas:** Clear the entire canvas using a dedicated button.
- **Real-Time Performance:** Efficiently handles drawing and gesture recognition in real-time.

## Installation

### Prerequisites

- Python 3.x
- OpenCV
- MediaPipe
- Numpy

### Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/virtual-paint.git
   cd virtual-paint
   ```

2. **Install the required packages:**
   ```bash
   pip install opencv-python mediapipe numpy
   ```

3. **Run the application:**
   ```bash
   python virtual_paint.py
   ```

## Usage

- **Drawing:** Move your index finger to draw on the canvas.
- **Switch Colors:** Move your hand over the color buttons at the top of the screen to switch the drawing color.
- **Clear Canvas:** Move your hand over the "CLEAR" button to erase everything on the canvas.
- **Exit:** Press the `q` key to exit the application.

## Project Structure

```plaintext
air_canvas/
├── air_canvas.py    # Main Python script
├── README.md           # Project documentation
└── requirements.txt    # List of dependencies (optional)
```

## How It Works

The application uses a combination of computer vision and hand tracking to interpret hand gestures as drawing commands. The index finger's movement is tracked in real-time and used to draw lines on a virtual canvas. The user can change colors or clear the canvas by interacting with on-screen buttons, all using hand gestures.

### Key Components:

- **OpenCV:** Used for image processing and displaying the canvas.
- **MediaPipe:** Provides the hand tracking functionality to detect hand landmarks.
- **Numpy:** Handles numerical operations, such as creating the canvas and managing the points for drawing.

## Acknowledgments

- [MediaPipe](https://mediapipe.dev/) by Google for providing the hand tracking solution.
- [OpenCV](https://opencv.org/) for the powerful computer vision tools.

---
