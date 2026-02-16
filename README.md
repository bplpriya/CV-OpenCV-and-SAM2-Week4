# CV-OpenCV-and-SAM2-Implementation

# Thermal Image Animal Boundary Segmentation

## Project Overview
This project focuses on identifying and extracting exact boundaries of animals from thermal imaging data. The core challenge is addressed using traditional Computer Vision techniques to separate heat signatures from backgrounds, followed by a comparative analysis against the state-of-the-art **Segment Anything Model 2 (SAM2)**.

## Features
- **Traditional Pipeline**: Noise reduction via Bilateral Filtering and automated thresholding using Otsu's Method.
- **Modern AI Benchmark**: Implementation of SAM2 for high-precision boundary extraction.
- **Accuracy Metrics**: Quantitative comparison using **Intersection over Union (IoU)**.
- **Visual Comparison**: Side-by-side visualization of original thermal data, OpenCV masks, and SAM2 results.

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.8+
- OpenCV (`cv2`)
- NumPy
- Matplotlib
- Ultralytics (for SAM2 implementation)

## Installation
```bash
pip install opencv-python ultralytics matplotlib numpy
