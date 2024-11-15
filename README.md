# Medical Image Segmentation with Otsu's Method and Genetic Algorithm

This repository contains a Jupyter Notebook that demonstrates the segmentation of brain medical images using a hybrid approach combining Otsu's thresholding method with a Genetic Algorithm (GA). This technique is tailored for medical image analysis to enhance segmentation accuracy in complex scenarios, such as brain imaging.

## Overview

Medical image segmentation is a critical step in medical image analysis, enabling the identification and separation of regions of interest, such as tumors or lesions, from the surrounding tissues. This project leverages:
- **Otsu's Method:** A global thresholding technique for image segmentation.
- **Genetic Algorithm (GA):** A metaheuristic optimization technique inspired by natural selection to improve the threshold selection process.

The hybrid method ensures better segmentation in images with varying contrast and intensity distributions, often seen in medical imaging.

---

## Features
- Implements Otsu's thresholding for initial segmentation.
- Optimizes the threshold selection using a Genetic Algorithm.
- Processes a sample brain medical image for segmentation.
- Provides clear visualizations of the original image, segmented output, and performance metrics.

---

## Requirements

The project is built using Python and Jupyter Notebook. Install the following dependencies to run the notebook:

- Python 3.11+
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib

You can install these packages via pip:

```bash
pip install numpy opencv-python matplotlib
