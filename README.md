# computer-vision-bougainvillea-analysis
A Computer Vision project demonstrating image processing, feature detection, feature extraction, segmentation, texture analysis, and colour-based localisation using a Bougainvillea flower image.
# Bougainvillea Image Analysis Using Computer Vision Techniques

## Project Overview

This project demonstrates the application of classical Computer Vision techniques on a Bougainvillea flower image.

The project performs image processing, feature detection, feature extraction, image segmentation, texture analysis, and colour-based localisation using Python.

## Objectives

The main objectives of this project are:

- To perform basic image preprocessing.
- To detect edges and corners.
- To detect lines and interest regions.
- To extract image features.
- To analyse gradients and textures.
- To apply different image segmentation techniques.
- To localise regions based on colour.
- To compare the results obtained using different Computer Vision methods.

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
computer-vision-bougainvillea-analysis/
│
├── README.md
├── requirements.txt
│
├── data/
│   └── bougainvilla.png
│
├── notebook/
│   └── computer_vision_analysis.ipynb
│
└── results/

Environment Setup
1. Install Python

Install Python 3.x on your system.

2. Create a Virtual Environment

Open a terminal in the project folder and run:

python -m venv venv

Activate the virtual environment.

Windows
venv\Scripts\activate
Linux/macOS
source venv/bin/activate
3. Install Dependencies

Install all required Python packages using:

pip install -r requirements.txt
Configuration

The input image used in this project is:

data/bougainvilla.png

The image is loaded and processed by the Computer Vision notebook.

How to Run the Project

Open a terminal in the project root directory.

Start Jupyter Notebook using:

jupyter notebook

Open the following notebook:

notebook/computer_vision_analysis.ipynb

Run the notebook cells sequentially from beginning to end.

The notebook performs all the image processing and Computer Vision operations included in the project.

Computer Vision Techniques Implemented
1. Edge and Corner Detection
Canny Edge Detection
Shi-Tomasi Corner Detection
Harris Corner Detection
2. Line and Interest Region Detection
Hough Line Detection
Difference of Gaussian (DoG)
Difference of Hessian (DoH)
3. Feature Extraction and Description
SIFT
HOG
Gradient Magnitude and Orientation
Log-Polar Transformation
4. Multi-Scale and Filter-Based Processing
Gaussian Smoothing at Multiple Scales
Laplacian Pyramid
Sobel Gradient
Gabor Filters
Haar Wavelet Transform
5. Image Segmentation
Otsu Thresholding
Region Growing
Edge-Based Segmentation
GrabCut
Mean Shift Segmentation
MRF/ICM Segmentation
Texture-Based Segmentation
6. Colour-Based Localisation
HSV Colour Segmentation
Morphological Processing
Contour Detection
Bounding-Box Localisation
Expected Output

The notebook generates visual outputs for the different Computer Vision techniques, including:

Edge maps
Corner visualisations
Detected line segments
Interest regions
SIFT feature visualisations
HOG feature representation
Gradient representations
Log-polar transformation
Gaussian smoothing results
Laplacian pyramid details
Sobel gradient components
Gabor filter responses
Haar wavelet components
Segmentation masks
Texture clusters
Colour-based regions
Bounding-box localisation
Input Data

The project uses a Bougainvillea flower image as the input.

Input file:

data/bougainvilla.png
Results

The results of the different Computer Vision techniques are displayed directly in the Jupyter Notebook.

The project allows comparison of different approaches for:

Edge detection
Corner detection
Feature extraction
Multi-scale image analysis
Image filtering
Image segmentation
Texture analysis
Colour-based localisation
Conclusion

This project demonstrates the application of various classical Computer Vision techniques to analyse a Bougainvillea flower image.

The implemented methods provide different ways to identify edges, corners, features, textures, regions, and colour-based structures within the image. The project also demonstrates how multiple segmentation techniques can produce different representations of the same input image.

The comparison of these techniques provides an understanding of their applications and behaviour in practical image analysis.
