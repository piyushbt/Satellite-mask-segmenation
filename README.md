****U-Net Model for Road Network Extraction from Satellite Images**

This repository contains the implementation of a U-Net model for extracting road networks from satellite images using PyTorch. The model is trained on RGB images with corresponding mask images for training, and it can predict road networks on new RGB images.
**Table of Contents**
•	Introduction
•	Dataset
•	Requirements
•	Model Architecture
•	Results
**Introduction**
The goal of this project is to develop a machine learning model that automatically extracts road networks from satellite images. The U-Net model is chosen for this task due to its effectiveness in image segmentation problems.
Dataset
The dataset consists of RGB satellite images and corresponding binary masks indicating the road networks. The images and masks should be organized in the following structure:
Image Folder
Mask Folder
**Requirements**
Install the required packages using pip:
•	Python 3.x
•	PyTorch
•	OpenCV
•	NumPy
•	scikit-learn
•	matplotlib


**Model Architecture**

•	The U-Net model is a convolutional neural network designed for biomedical image segmentation. The architecture consists of an encoder (downsampling path), a bottleneck, and a decoder (upsampling path).
 
![image](https://github.com/user-attachments/assets/73a60da8-4872-4cfd-8e7c-f842b0b4c3d6)

Results
•	Training and validation losses are printed during the training process. You can also visualize the predictions using matplotlib.
 
![image](https://github.com/user-attachments/assets/b2fe1c21-7bc1-4f49-8bd6-16f428a42da8)



