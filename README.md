# OpenCV notebooks
This repository contains notebooks in computer vision tasks using the OpenCV library,
including:
### * [Face swapping using opencv and Dlib](https://github.com/rasoulasadiyan/OpenCV/blob/master/01_Face_Swapping.ipynb):
Dlib's face detection and shape prediction models are utilized to detect faces in both images and extract facial landmarks. These landmarks are essential for aligning and swapping the faces accurately.
After calculating the ConvexHull, the faces are divided into triangles, then the corresponding triangles are resized and swapped.Finally SeamlessClone used to seamlessly integrate the swapped face onto the target image while maintaining natural-looking textures and lighting conditions.
   
### * [Skin detection in color spaces](https://github.com/rasoulasadiyan/OpenCV/blob/master/02_Skin-detection-using-color-space-masks.ipynb):
This code provides a comprehensive demonstration of image segmentation and filtering techniques using OpenCV. It explores the use of different color spaces(BGR, HSV, YCRCB and combination of them) and masks to extract Skin areas from images and applies various filtering and morphology operations for image enhancement and noise reduction.

### * [SIFT-feature matching](https://github.com/rasoulasadiyan/OpenCV/blob/master/03_SIFT_feature-matching.ipynb):
Dlib's face detection and shape prediction models are utilized to detect faces in both images and extract facial landmarks. These landmarks are essential for aligning and swapping the faces accurately.
After calculating the ConvexHull, the faces are divided into triangles, then the corresponding triangles are resized and swapped.Finally SeamlessClone used to seamlessly integrate the swapped face onto the target image while maintaining natural-looking textures and lighting conditions.

### * [Object tracking](https://github.com/rasoulasadiyan/OpenCV/blob/master/07_Object-tracking-using-cv2-trackers.ipynb):
This code use various tracking algorithms provided by OpenCV(such as BOOSTING, MEDIANFLOW, MIL, KCF,GOTURN,...).
The code is designed to work with video input and utilizes pretrained models for object detection.

### * [Target face recognition](https://github.com/rasoulasadiyan/OpenCV/blob/master/04_Target-face-recognition.ipynb):
The code utilizes a pre-trained face detection, recognition model and matches detected faces with known faces using a similarity threshold.

Other notebooks relating pose , 
