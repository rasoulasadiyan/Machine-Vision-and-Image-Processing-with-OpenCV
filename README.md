# OpenCV notebooks
This repository contains notebooks in computer vision tasks using the OpenCV library,
including:
### * [Face swapping using opencv and Dlib](https://github.com/rasoulasadiyan/OpenCV/blob/master/01_Face_Swapping.ipynb):
Dlib's face detection and shape prediction models are utilized to detect faces in both images and extract facial landmarks. These landmarks are essential for aligning and swapping the faces accurately.
After calculating the ConvexHull, the faces are divided into triangles, then the corresponding triangles are resized and swapped.Finally SeamlessClone used to seamlessly integrate the swapped face onto the target image while maintaining natural-looking textures and lighting conditions.

![Screenshot from 2023-09-16 03-04-39](https://github.com/rasoulasadiyan/OpenCV/assets/100882487/a8d2ba96-4a02-431c-bc09-3da39d473934)


   
### * [Skin detection in color spaces](https://github.com/rasoulasadiyan/OpenCV/blob/master/02_Skin-detection-using-color-space-masks.ipynb):
This code provides a comprehensive demonstration of image segmentation and filtering techniques using OpenCV. It explores the use of different color spaces(BGR, HSV, YCRCB and combination of them) and masks to extract Skin areas from images and applies various filtering and morphology operations for image enhancement and noise reduction.

![Screenshot from 2023-09-16 03-27-55](https://github.com/rasoulasadiyan/OpenCV/assets/100882487/6018c6e3-a581-4eb5-bfb0-e5d848ea6d25)



### * [SIFT-feature matching](https://github.com/rasoulasadiyan/OpenCV/blob/master/03_SIFT_feature-matching.ipynb):
The code will compare each novel image with the reference image and display the results, highlighting potential matches and perspective corrections.
It uses computer vision techniques and the SIFT (Scale-Invariant Feature Transform) algorithm to find similarities between images.

![Screenshot from 2023-09-16 03-12-06](https://github.com/rasoulasadiyan/OpenCV/assets/100882487/de72120d-ee3f-4212-b704-710c804542ed)


### * [Object tracking](https://github.com/rasoulasadiyan/OpenCV/blob/master/07_Object-tracking-using-cv2-trackers.ipynb):
This code use various tracking algorithms provided by OpenCV(such as BOOSTING, MEDIANFLOW, MIL, KCF,GOTURN,...).
The code is designed to work with video input and utilizes pretrained models for object detection.

### * [Target face recognition](https://github.com/rasoulasadiyan/OpenCV/blob/master/04_Target-face-recognition.ipynb):
The code utilizes a pre-trained face detection, recognition model and matches detected faces with known faces using a similarity threshold.

Other notebooks relating about [Pose](https://github.com/rasoulasadiyan/OpenCV/blob/master/06_Posture-recognition-using-pretrained-pose-estimation-model.ipynb) , [Intractive tracking](https://github.com/rasoulasadiyan/OpenCV/blob/master/10_Camshift_tracker.ipynb), [Connected Components](https://github.com/rasoulasadiyan/OpenCV/blob/master/08_Connected%20Components_binarization.ipynb), [Equalization](https://github.com/rasoulasadiyan/OpenCV/blob/master/05_CLAHE_Histogram-equalization.ipynb), [Linear Brightness](https://github.com/rasoulasadiyan/OpenCV/blob/master/11_Linear%20brightness_gamma%20correction.ipynb.ipynb), ...  

