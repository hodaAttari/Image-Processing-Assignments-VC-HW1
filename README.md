## Computer Vision – Homework 1
---
Image Processing Basics with OpenCV and NumPy

This repository contains three Jupyter notebooks for the first assignment of an introductory Computer Vision course. The notebooks demonstrate core image processing concepts such as image loading, filtering, histogram analysis, and RGB-to-HSV color-space transformation using OpenCV, NumPy, and Matplotlib.

#### Filters.ipynb

This notebook introduces image loading and visualization using OpenCV and Matplotlib, followed by basic filtering operations. It implements mean filtering, Gaussian filtering, and image sharpening using the Unsharp Mask technique. The notebook provides a practical foundation for understanding how linear filters affect noise, smoothness, and detail.

#### Histogeram.ipynb

This notebook focuses on statistical analysis of image intensity. It computes the histogram of an image and derives the PDF and CDF. It also applies contrast stretching to expand the dynamic range of pixel intensities. The outputs illustrate how intensity distribution influences image visibility and contrast.

#### ColorSpaces.ipynb

This notebook introduces color-space transformations. It reads an image, converts it from RGB to HSV, and separates the H, S, and V channels for analysis. It also extracts luminance and demonstrates why HSV is widely preferred in segmentation and recognition tasks due to its separation of chromatic and intensity information.

####  Requirements

- Python 3
- OpenCV
- NumPy
- Matplotlib

#### Install the required libraries using:
```bash
pip install opencv-python numpy matplotlib
```
#### How to Run

Clone the repository, open the notebooks in Jupyter Notebook or VSCode, and run the cells in order. Each notebook is self-contained and requires no additional files.
