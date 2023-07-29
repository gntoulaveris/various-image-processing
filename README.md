# various-image-processing

# Overview
This project was done with the goal of exploring various image preprocessing techniques that could then be applied to more complex image analysis projects. It involves processing of different kind of images and covers transformations, corrections, object detection and object isolation. 

# Analysis 1 - Image Transformation
This analysis involved the transformation of images under the following transformation function. The results of the transformation can be changed by using another transformation function. The transformed images are compared side-by-side with their original ones.

<p align="center">
  <img src="transformation_function.png" alt="Analysis 1-Transformation function" width="400">
</p>

<p align="center">
  <img src="einstein_transformed.png" alt="Analysis 1-Transformed Einstein Image" width="1000">
</p>

<p align="center">
  <img src="forest_transformed.png" alt="Analysis 1-Transformed Forest Image" width="1000">
</p>


# Analysis 2 - Image Enhancement
This analysis had the goal to enhance an image. One method of image enhancement could be color balance adjustment. This technique adjusts the color balance and can thus help to improve the overall color tone of the image. It can be used to bring out more natural-looking colors in the image. Another technique that could be applied is Histogram equalization. This is a technique for adjusting the contrast of an image by modifying the image's histogram. It can help to bring out more details in both the bright and dark areas of the image.

## 1. Color Balance Adjustment

<p align="center">
  <img src="forest_color_balanced.png" alt="Analysis 2-Color Balanced Forest Image" width="1000">
</p>

## 2. Histogram equalization

<p align="center">
  <img src="forest_hist_equalized.png" alt="Analysis 2-Histogram Equalized Forest Image" width="1000">
</p>


# Analysis 3 - Brightness Improvement
The goal of this analysis was to improve the image in terms of perceived brightness. One technique that can achieve that is Gamma correction. This technique involves applying a nonlinear adjustment to the pixel values in an image to change its brightness and contrast.

<p align="center">
  <img src="pollen_gamma_correction.png" alt="Analysis 3-Gamma corrected Pollen Image" width="1000">
</p>


# Analysis 4 - Image Sharpening
The goal of this analysis was the sharpening of images. Two techniques were applied and compared. The first one was the Unsharp Masking technique. The second was the Negative Sharpening technique. Negative sharpening produced much better results than the Unsharp Masking. 

## 1. Unsharp Masking

<p align="center">
  <img src="moon_unsharp_masking.png" alt="Analysis 4-Unsharp Masking Moon Image" width="1000">
</p>

## 2. Negative Sharpening

<p align="center">
  <img src="moon_negative_sharpening.png" alt="Analysis 4-Negative Sharpening Moon Image" width="1000">
</p>


# Analysis 5 - Recreation of transformed image
In this analysis two versions of the same image were used, the original and a transformed one with unknown transformations applied to it. The analysis involved the assessment of the uknown transformations and the transformation of one image to the other and vice-versa. The two images can be seen below.

## 1. From original to transformed image
The transformed image was used as reference for the transformation