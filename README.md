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

Implementation 02 :
# Image Segmentation using GrabCut and Thresholding

This project demonstrates two methods to perform **image segmentation** and extract foreground objects such as a fruit, a person, or any prominent shape using OpenCV.

## ✨ Features

- GrabCut-based segmentation using a rectangle to isolate the foreground
- Thresholding + contour-based segmentation
- Side-by-side visual comparison
- Easy to switch and test on different images

 #### 📌 Comparison
| Feature | GrabCut | Threshold + Contours |
|--------|---------|-----------------------|
| Accuracy | High (adaptive) | Medium (depends on contrast) |
| Input | RGB + rectangle | Grayscale |
| Robustness | Works well with complex backgrounds | Limited to clean backgrounds |

# 📌 Shi-Tomasi Corner Detection using OpenCV

This project demonstrates the Shi-Tomasi algorithm to detect and visualize corner points in an image.

## 🧠 What is Shi-Tomasi?
Shi-Tomasi is a corner detection algorithm used to identify strong interest points in an image. These corners can be used in further tasks like object tracking, motion estimation, and 3D reconstruction.

## 🎯 Features
- Detects up to 100 strongest corners in an image
- Marks them with green circles
- Easy to apply on any image


## ⚙️ Requirements

- Python 3.x
- OpenCV

Install dependencies using:

```bash
pip install opencv-python
