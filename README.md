# Basic-Image-Operations

In these notebooks I am going to show how to make basic image operations.

## 1. Arithmetic Operations

The notebook for arithmetic operations I use some useful functions from numpy for brightness like ones.
For the brightness I use the functions from opnecv (add and subtract).

For the contrast of an image I use the multiply function from opencv, the first step is create a matrix with the same shape of the
original image with a constant value, then the useful functions from numpy like uint8 and clip.

## 2. Thresholding

In this notebook I use some techniques for thresholding.

The thresholding is a process to convert a grayscale image to a binary image where the pixels belong two categories (normally black and white).

The function threshold is very useful here for this case, it return two values, the first is the threshold value, the second is the binary image.
The four required arguments are:
1. Image: This is the grayscale image we want to convert in binary.
2. Threshold: The value of the threshold.
3. MaxVal: The value of the pixels greater than Threshold.
4. The type of threshold.
