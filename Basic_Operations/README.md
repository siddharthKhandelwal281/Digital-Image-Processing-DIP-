# Basic Image Operations – Digital Image Processing

## Overview
This experiment demonstrates **basic image processing operations** using MATLAB as part of the **Digital Image Processing (DIP) laboratory**. The objective is to understand how digital images are represented and how simple operations can be performed on them.

---

## Operations Performed

### 1. Random Matrix Generation
An 8×8 matrix with random integer values in the range **0–255** is generated.  
This matrix simulates a small **grayscale image**, where each value represents a pixel intensity.

---

### 2. Image Acquisition
A color image is read from the system using MATLAB’s image reading function.  
The original RGB image is displayed for reference.

---

### 3. RGB to Grayscale Conversion
The input RGB image is converted into a **grayscale image** to represent intensity information using a single channel.

---

### 4. Color Channel Extraction
The **red channel** of the RGB image is extracted by removing the green and blue channels.  
This operation helps in understanding color plane slicing.

---

### 5. Binary Image Generation
The grayscale image is converted into a **binary image** using a fixed threshold value.  
Pixels above the threshold are assigned white, and others are assigned black.

---

### 6. Histogram Equalization
Histogram equalization is applied to the grayscale image to **enhance contrast** and improve visibility of image details.

---

## Tools Used
- MATLAB
- Digital Image Processing functions

---

## Purpose
The purpose of this experiment is to gain practical understanding of:
- Image representation as matrices
- Grayscale conversion
- Color channel manipulation
- Thresholding
- Image enhancement techniques



