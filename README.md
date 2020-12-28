# Face_Recognition
Face Recognition project
Keywords: Python, TensorFlow, Deep Learning, LBPH

Table of contents
1. Installation
2. Problem Statement
3. Dataset
4. Introduction
5. How to run
6. Resources

Steps: 
1. Installation
   This project was designed for:
   Python 3.6
   TensorFlow 1.12.0

2. Problem Statement:
   Design the image based capturing system using deep learning and computer vision.

3. Dataset: https://drive.google.com/file/d/12_WTFi9ppvD-loaWUWpUar25Z3nT5k9P/view

4. Introduction
I have used LBPH here
Local Binary Pattern Histogram(LBPH)
The Local Binary Pattern Histogram(LBPH) algorithm is a simple solution
 on face recognition problem, which can recognize both front face and 
side face.
LBP is popular in texture recognition and is used for the facial 
features extraction and detection has been used. The local binary 
operator is used for the calculation of binary patterns in digital
 images. The extracted features of the input images are displayed 
using the binary image. Binary images used two-pixel values and color 
black and white. The calculation of the local binary pattern is shown 
in fig. A comparison of every 
neighboring pixel is done with the center pixel is done.
 If the neighbor pixel value is greater or equal (>=) to the 
center pixel value than we will assign 1 and if the neighbor
 pixel is smaller (<) than the central pixel than assign 0.
 
5. How to run :
   a. Download the datasets and make changes in the location of datasets in train and load file.
   b. Directly run the load_image file , everyting I have linked , so there is no need to run each file
      separately, load_image file is enough, if you want the attendance to be done through video then,
      run load_video file.
      Note: Make sure the file location is correctly done.

6. Resources:
    a. https://www.youtube.com/watch?v=sz25xxF_AVE
    b. https://www.youtube.com/watch?v=ukL_UjrqZFw&t=306s
