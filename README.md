﻿# CV-Mini-Project

Implementation 01:
# Face Detection and Privacy Blur using OpenCV

This project detects human faces in images and webcam feed using OpenCV's Haar Cascade classifier and applies a Gaussian blur to anonymize the detected faces. It is useful in scenarios where privacy must be preserved, such as CCTV footage or media publications.

## 💡 Project Overview

- 🔍 Detects faces using Haar Cascade (pre-trained XML classifier)
- 🖼️ Blurs detected faces in static images
- 🎥 Real-time face detection and blur from webcam feed (optional)
- 💾 Saves the processed image with blurred faces

## 📁 Files

| File | Description |
|------|-------------|
| `face_blur.py` | Main Python script for face detection and blur |
| `haarcascade_frontalface_default.xml` | Haar cascade model file for face detection |
| `facejpg` | (Optional) Sample image to test face blurring |
| `blurred_output.jpg` | Output image with blurred faces |
| `README.md` | This file |




## ⚙️ Requirements

- Python 3.x
- OpenCV

Install dependencies using:

```bash
pip install opencv-python
