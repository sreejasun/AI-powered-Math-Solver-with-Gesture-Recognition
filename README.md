# AI-Powered Math Solver with Gesture Recognition

This project combines computer vision and AI to create a unique hand gesture-based painting application that can solve mathematical equations drawn by users. The application leverages OpenCV, MediaPipe, and Streamlit for hand gesture recognition, drawing interface, and AI-based equation solving.

---

## Features

- **Hand Gesture-Based Drawing**: Use hand gestures to draw on a virtual canvas.
- **Color Selection and Clear Canvas**: Switch between colors (Blue, Green, Red) or clear the canvas using gesture-based controls.
- **AI Math Solver**: Automatically recognizes and solves mathematical equations drawn on the canvas.
- **Streamlit UI**: Live video feed and drawing canvas displayed in the browser.

---

## How It Works

1. **Draw on the Canvas**: Use hand gestures detected by a webcam to draw.
2. **Select Colors**: Gesture over the color boxes (Blue, Green, Red) to change the drawing color.
3. **Submit for Solution**: Gesture over the "SUBMIT" button to save the canvas and send the image to an AI model for solving.
4. **Result Display**: The solution to the mathematical equation is displayed on the canvas.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sreejasun/AI-powered-Math-Solver-with-Gesture-Recognition.git
   cd AI-powered-Math-Solver-with-Gesture-Recognition
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the application:
   ```bash
   streamlit run app.py

  ---
  
## Usage

1. Launch the app and allow webcam access.
2. Use hand gestures to draw, clear, or submit the canvas.
3. Upon submission, the drawn equation is solved using AI, and the result is displayed.

---

## Acknowledgments:

This project uses:

- OpenCV for image processing.
- MediaPipe for hand tracking.
- Streamlit for the web interface.
- AI model for equation solving via the OpenAI API.
