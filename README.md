# Facial Keypoint Detection

## Overview
This project are part of Computer vision Nanodergee via Udacity. Facial keypoints  specify the areas of the nose, eyes, mouth, etc on the face, classified by 68 key points. Using CNN, pytorch and opencv build a facial keypoint detection system that takes any images with human faces and detect main 68 keypoints.

## Structure

Project split in 3 main notebooks and models.py file.

1) models.py -- Model architecture.
2) Load and Visualize Data.ipynb -- Loading and Visualizing the Facial Keypoint Data
3) Define the Network Architecture.ipynb -- Defining and Training a Convolutional Neural Network (CNN) to Predict Facial Keypoints.
4) Facial Keypoint Detection, Complete Pipeline.ipynb --Facial Keypoint Detection Using Haar Cascades and your Trained CNN.
5) Fun with Keypoints.ipynb -- Fun expiriements with keypoints.

## Examples

### Haar Cascade
<p align="center"> <img src="images/haar_cascade_ex.png" align="middle" alt="drawing" width="1600px"> </p> 

### Facial Keypoints
<p align="center"> <img src="images/michelle_detected.png" align="middle" alt="drawing" width="800px"> </p> 

## Instalation

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
	```
	git clone https://github.com/DeividasMat/facial_keypoint_detection
  
2. Create (and activate) a new Anaconda environment (Python 3.6).
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

3. Install PyTorch and torchvision; this should install the latest version of PyTorch;
```
conda install pytorch torchvision cudatoolkit=9.0 -c pytorch
```
6. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt


## Licence
This project is licensed under the terms of the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
