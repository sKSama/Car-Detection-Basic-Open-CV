# Car-Detection-Basic-Open-CV

Video Tutorial - https://youtu.be/RlD7Q6GFFJE

![](http://img.youtube.com/vi/RlD7Q6GFFJE/0.jpg)](http://www.youtube.com/watch?v=RlD7Q6GFFJE "VIDEO TUTORIAL ")

Description: This project uses __OpenCV Library__ which is is an open source computer vision and machine learning software library.
HaarCascade: It is a machine learning object detection algorithm used to identify objects in an image or video.
With the combination of Python and CV2, image of cars are extracted from video and displayed on windows Screen.

## A little about OpenCV -

OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products. Being a BSD-licensed product, OpenCV makes it easy for businesses to utilize and modify the code.

The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms. These algorithms can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects, extract 3D models of objects, produce 3D point clouds from stereo cameras, stitch images together to produce a high resolution image of an entire scene, find similar images from an image database, remove red eyes from images taken using flash, follow eye movements, recognize scenery and establish markers to overlay it with augmented reality, etc. OpenCV has more than 47 thousand people of user community and estimated number of downloads exceeding 18 million. The library is used extensively in companies, research groups and by governmental bodies.

## Haarcascades -

Haar Cascade classifiers are an effective way for object detection. This method was proposed by Paul Viola and Michael Jones in their paper Rapid Object Detection using a Boosted Cascade of Simple Features .Haar Cascade is a machine learning-based approach where a lot of positive and negative images are used to train the classifier.

* Positive images – These images contain the images which we want our classifier to identify.
* Negative Images – Images of everything else, which do not contain the object we want to detect.

## Installation:
1. Below packages to be installed using the CLI :

    - Numpy `pip install numpy`.
    - Matplotlib `pip install matplotlib` (Matplotlib is optional, but recommended since we use it a lot in our tutorials).
    - OpenCV `pip install opencv-python`
    
2. Install all packages into their default locations. Python will be installed to C:/Python27/ in case of Python 2.7.
3. After installation, open Python IDLE. Enter `import numpy` and make sure numpy is working fine.
4. After installation, open Python IDLE and type in the following lines and execute the file (This is just to check if everything is working fine):<br>
  `import numpy`<br>
  `import matplotlib`<br>
  `import cv2 as cv`<br>
  `print( cv.__version__ )`
5. If the file executes without an error, Congratulations, you have successfully completed the installation part.

### You will cover the following topics while building this project:
1) Frame Differencing
2) Image Thresholding
3) Contours
4) Image Dilation

## Output:

![Output Img#1](https://github.com/SarthakRana/Car-Detection-Basic-Open-CV/blob/master/output_img1.png?raw=true)
![Output Img#1](https://github.com/SarthakRana/Car-Detection-Basic-Open-CV/blob/master/output_img2.png?raw=true)
![Output Img#1](https://github.com/SarthakRana/Car-Detection-Basic-Open-CV/blob/master/output_img3.png?raw=true)
