# CAPTCHA Solver Using Python and OpenCV
This repository contains the implementation of a CAPTCHA solver that preprocesses CAPTCHA images using Python and OpenCV. The CAPTCHA dataset used in this project is collected from the Election Commission of India. The goal of this project is to preprocess CAPTCHA images for further analysis or automated solving.

## Features
CAPTCHA Preprocessing: Leverages OpenCV to preprocess CAPTCHA images by applying techniques like binarization, noise reduction, and segmentation.
Dataset Source: CAPTCHA images are sourced from the Election Commission of India.
Customizable: Code is modular, allowing easy adjustments for different CAPTCHA formats.

## Prerequisites
Ensure you have the following installed on your system:

Python (>=3.7)

OpenCV (cv2)

NumPy

## How It Works

Loading Images: Reads CAPTCHA images from the data/ directory.

Preprocessing: Applies various OpenCV techniques such as:

Grayscale conversion

Thresholding

Morphological transformations

Noise reduction

Output: Saves the preprocessed images in the output/ folder.

## Acknowledgments

The CAPTCHA dataset is collected from the Election Commission of India.

OpenCV documentation and community for their invaluable resources.
