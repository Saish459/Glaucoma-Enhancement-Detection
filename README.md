# Glaucoma Image Enhancement and Segmentation

This repository contains Python code for enhancing glaucoma eye color images and proposing an image segmentation method for glaucoma detection. The project utilizes the OpenCV library for image processing and manipulation, as well as Matplotlib for visualizing the results in a Jupyter Notebook environment.

## Enhancement of Glaucoma Eye Color Image ✨

The initial part of the project focuses on enhancing glaucoma eye color images to improve visibility and aid in subsequent analysis. The following steps are performed:

1. **Loading the Image:**  The glaucoma eye color image is loaded using OpenCV.
2. **Grayscale Conversion:**  The image is converted to grayscale to simplify processing.
3. **Noise Reduction:** Gaussian filtering is applied to reduce noise in the grayscale image.
4. **CLAHE (Contrast Limited Adaptive Histogram Equalization):** CLAHE is independently applied to each color channel to enhance contrast in the image.
5. **Display:** The original and enhanced images are displayed side by side in the Jupyter Notebook.

## Proposed Image Segmentation Method with CDOD-Glaucoma 🎯

The second part of the project introduces a proposed image segmentation method for glaucoma detection using CDOD-Glaucoma (Color Segmentation with Optic Disc Detection for Glaucoma). The steps are as follows:

1. **Loading the Image:**  The glaucoma eye color image is loaded using OpenCV.
2. **Grayscale Conversion:**  The image is converted to grayscale for further processing.
3. **Optic Disc Detection:**  Circular Hough transform is used to detect the optic disc in the grayscale image. The detected disc is outlined in red.
4. **Blood Vessel Segmentation:** Binary vessel segmentation is performed using a thresholding technique.
5. **Glaucoma Detection:** The optic disc and blood vessel segmentation are combined to visualize glaucoma-affected regions in the image.
6. **Display:** The original color image, segmented optic disc, and detected glaucoma-affected regions are displayed for analysis.

##### This project is for educational and research purposes and is not intended for medical diagnosis. Consult with healthcare professionals for accurate medical assessments.
