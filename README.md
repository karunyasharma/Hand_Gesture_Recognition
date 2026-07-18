# Sign Language to Text Converter

**Author:** Karunya Sharma 

## Introduction
Millions of people use sign language to communicate, but a significant barrier exists for non-signers to understand it. 
The objective of this project is to convert sign language gestures into readable text in real-time using a webcam and AI.

## How It Works
1. **Capture:** The webcam captures hand signs.
2. **Preprocessing:** Image processing is used to isolate hand gestures.
3. **Recognition:** A machine learning model classifies the hand signs.
4. **Translation:** Recognized signs are converted into corresponding text.
5. **Display:** Text output is displayed to the user.

## Key Technologies Used
* **Environment:** Google Colab 
* **Deep Learning:** Google Teachable Machine for gesture recognition 
* **Programming & Libraries:** Python, TensorFlow, Keras, OpenCV 
* **Hardware:** Webcam or built-in camera 

## Applications
* Aid for deaf and mute individuals.
* Educational tools.
* Real-time communication in public services.
* Integration into virtual assistants.

## Setup Instructions
1. Clone this repository.
2. Train a model using [Google Teachable Machine](https://teachablemachine.withgoogle.com/) and export it as an H5 Keras model.
3. Place `keras_model.h5` and `labels.txt` into the `/models/` directory.
4. Upload `Sign_Language_Colab.ipynb` to Google Colab and run all cells.
