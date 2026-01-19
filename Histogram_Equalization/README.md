# Histogram Equalization

## Aim
To perform histogram equalization on a grayscale image without using MATLAB’s built-in `histeq()` function.

---

## Description
In this experiment, histogram equalization is implemented step by step to improve the contrast of an image. The process involves calculating the histogram, probability density function (PDF), cumulative distribution function (CDF), and mapping old pixel values to new intensity values.

The input image is first converted to grayscale (if required) and then processed using the histogram equalization algorithm.

---

## Steps Followed
1. Read the input image.
2. Convert the image to grayscale if it is RGB.
3. Calculate the histogram of pixel intensities.
4. Compute the PDF from the histogram.
5. Compute the CDF from the PDF.
6. Normalize the CDF values.
7. Map the original pixel values to new equalized values.
8. Display the original and equalized images along with their histograms and CDFs.

---

## Observations
- The original image has uneven intensity distribution.
- After histogram equalization, pixel values are more uniformly distributed.
- Image contrast is improved in the equalized image.

---

## Conclusion
Histogram equalization enhances image contrast by redistributing pixel intensity values. Implementing the algorithm step by step helps in understanding histogram, PDF, CDF, and intensity mapping concepts used in Digital Image Processing.

---

## Tools Used
- MATLAB
- Digital Image Processing concepts

