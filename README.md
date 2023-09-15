# OpenCV notebooks
This repository contains notebooks in computer vision tasks using the OpenCV library,
including:
### 1. [Face swapping using opencv and Dlib](https://github.com/rasoulasadiyan/OpenCV/blob/master/01_Face_Swapping.ipynb):
Dlib's face detection and shape prediction models are utilized to detect faces in both images and extract facial landmarks. These landmarks are essential for aligning and swapping the faces accurately.
After calculating the ConvexHull, the faces are divided into triangles, then the corresponding triangles are resized and swapped.Finally SeamlessClone used to seamlessly integrate the swapped face onto the target image while maintaining natural-looking textures and lighting conditions.
   
### 1. [Skin detection in color spaces](https://github.com/rasoulasadiyan/OpenCV/blob/master/02_Skin-detection-using-color-space-masks.ipynb):
This code provides a comprehensive demonstration of image segmentation and filtering techniques using OpenCV. It explores the use of different color spaces(BGR, HSV, YCRCB and combination of them) and masks to extract Skin areas from images and applies various filtering and morphology operations for image enhancement and noise reduction.



