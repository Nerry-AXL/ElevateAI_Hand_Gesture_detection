Hand Gesture Detection

This repository contains the source code for the ElevateAI Hand Gesture Detection system, an application that recognizes and interprets hand gestures in real-time using computer vision and machine learning techniques. The system is designed to facilitate human-computer interaction by allowing users to control devices or interfaces using hand gestures.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)


## Project Overview

The ElevateAI Hand Gesture Detection system uses advanced deep learning models to detect and classify hand gestures from video feeds. This technology can be applied in various fields, including virtual reality, gaming, sign language recognition, and touchless control systems.

## Features

- **Real-Time Gesture Detection:** Detect and classify hand gestures in real-time using a webcam or video feed.
- **Custom Gesture Recognition:** Support for training and recognizing custom gestures.
- **User-Friendly Interface:** Simple interface for capturing video input and displaying detected gestures.
- **Gesture-Controlled Actions:** Ability to map detected gestures to specific actions or commands.

## Installation

To run the ElevateAI Hand Gesture Detection system locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Nerry-AXL/ElevateAI_Hand_Gesture_detection.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd ElevateAI_Hand_Gesture_detection
    ```

3. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

### Dependencies

The main dependencies for this project include:

- Python 3.x
- TensorFlow / PyTorch (depending on the model used)
- OpenCV
- MediaPipe (for hand tracking)
- NumPy
- Streamlit (for web-based interface)
- Matplotlib (for visualization)

## Usage

1. **Start the application:**

    ```bash
    python app.py
    ```

2. **Access the app interface:**
   Open your web browser and navigate to `http://127.0.0.1:5000/` to access the ElevateAI Hand Gesture Detection interface.

3. **Begin gesture detection:**
   Use a webcam or upload a video file to start detecting and classifying hand gestures.

4. **Custom Gesture Integration:**
   To add custom gestures, follow the instructions in the `custom_gestures/` directory and update the model training code accordingly.

## Model Details

- **Pre-trained Models:** The system includes pre-trained models for basic hand gesture recognition (e.g., thumbs up, peace sign).
- **Custom Models:** Users can train custom models to recognize new hand gestures using the provided scripts.

### Hand Tracking

- **MediaPipe:** Used for real-time hand tracking and landmark detection, providing precise hand position and finger movements.

### Gesture Classification

- **CNN (Convolutional Neural Networks):** Employed to classify hand gestures based on the input images or video frames.
- **Transfer Learning:** Techniques like transfer learning can be applied to adapt pre-trained models to custom gesture datasets.

## Results

The Hand Gesture Detection system provides detailed feedback on detected gestures, including:

- Visualization of detected hand landmarks.
- Classification labels for recognized gestures.
- Confidence scores for gesture predictions.

## Contributing
Contributions to this project are welcome! If you have ideas for new features, improvements, or bug fixes, feel free to fork the repository, make your changes, and submit a pull request.
