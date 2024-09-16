# Pencil Sketch Application with Flask and OpenCV

This project is a simple web-based application that allows users to create real-time pencil sketches from their webcam feed. The application uses OpenCV for image processing and Flask for the web interface. Users can start, restart, or stop the camera feed and apply the pencil sketch effect directly from the web interface.

## 🚀 Overview

The **Pencil Sketch Application** captures video input from the webcam, applies image processing techniques such as sharpening and grayscale conversion, and outputs a real-time pencil sketch effect. The project also includes a simple Flask-based UI with buttons to control the application.

## ✨ Features

- **Real-time Video Feed**: Captures video from the webcam and applies a pencil sketch effect in real-time.
- **Sharpened Image Output**: Uses a kernel to sharpen the captured frame before applying the sketch effect.
- **Simple Web Interface**: A Flask web application with buttons to start, restart, or stop the process.
- **Pencil Sketch Effect**: Converts the sharpened image into a pencil sketch using OpenCV's `divide()` function and Gaussian Blur.

## 🛠️ Installation

To set up and run the project locally, follow these steps:

### Clone the Repository

```bash
git clone https://github.com/your-github-username/pencil-sketch-app.git
cd pencil-sketch-app
