# Face Swap Project using InsightFace

This repository contains a **Face Swap** project implemented using the [InsightFace](https://github.com/deepinsight/insightface) library, a powerful open-source deep learning framework for face recognition, face analysis, and face swapping. The project swaps faces between two given images while maintaining facial features and structure using advanced deep learning models.

## Project Overview

The **Face Swap** project leverages the InsightFace library to detect and align faces, perform face swapping, and blend the results seamlessly. InsightFace provides pre-trained models for facial recognition and landmark detection, which are essential for accurate face swapping.

## Features

- High-accuracy face detection and alignment using InsightFace models.
- Face swapping between images with minimal distortion.
- Preserves facial landmarks for realistic results.
- Blends the swapped faces using image processing techniques.

## Requirements

To run this project, you'll need the following dependencies:

- Python 3.x
- InsightFace
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

Install the required libraries using:

```bash
pip install insightface opencv-python numpy matplotlib
