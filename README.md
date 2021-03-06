# Facial Keypoint Detection

## Overview
This project is part of Computer vision Nanodergee via Udacity. Facial keypoints specify the areas of the nose, eyes, mouth, etc on the face, classified by 68 key points. Using CNN, Pytorch, and OpenCV I built a facial keypoint detection system that takes images with human faces and detects main facial keypoints.

## Structure

Project split in 3 main notebooks and models.py file.

1) models.py -- Model architecture.
2) Load and Visualize Data.ipynb -- Loading and Visualizing the Facial Keypoint Data
3) Define the Network Architecture.ipynb -- Defining and Training a Convolutional Neural Network (CNN) to Predict Facial Keypoints.
4) Facial Keypoint Detection, Complete Pipeline.ipynb --Facial Keypoint Detection Using Haar Cascades and your Trained CNN.
5) Fun with Keypoints.ipynb -- Fun experiments with keypoints.

## Examples

### Haar Cascade
<p align="center"> <img src="images/haar_cascade_ex.png" align="middle" alt="drawing" width="1600px"> </p> 

### Facial Keypoints
<p align="center"> <img src="images/michelle_detected.png" align="middle" alt="drawing" width="800px"> </p> 

## Instalation

1. Clone the repository
	```
	git clone https://github.com/DeividasMat/facial_keypoint_detection
	```
  
2. Create and activate Anaconda environment (Python 3.6).
Download via [Anaconda](https://www.anaconda.com/distribution/)

	- __Linux__ or __Mac__: 
	```
	conda create -n cv-nd python=3.6
	source activate cv-nd
	```
	- __Windows__: 
	```
	conda create --name cv-nd python=3.6
	activate cv-nd
	```

3. Install PyTorch and torchvision
```
conda install pytorch torchvision cudatoolkit=9.0 -c pytorch
```
6. Install a few required using pip or conda

	- opencv-python==3.2.0.6
	- matplotlib==2.1.1
	- pandas==0.22.0
	- numpy==1.12.1
	- pillow>6.2.0
	- scipy==1.0.0
	- torch>=0.4.0
	- torchvision>=0.2.0
	

## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
