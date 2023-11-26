# Our Project
Real-time implementation of Semantic Segmentation for traffic detection and autonomous driving applications. 
# Table of contents
- [About the Project](#About-the-Project)
  - [Tech Stack](#Tech-Stack)
  - [File Structure](#File-Structure)
- [Getting Started](#Getting-Started)
  - [Prerequisites and installlation](#Prerequisites-and-installlation)
  - [Installation](#Installation)
  - [Execution](#Execution)
- [Theory and Approach](#Theory-and-Approach)
-  [Results and Demo](#Results-and-Demo)
-  [Future Work](#Future-Work)
-  [Contributors](#Contributors)
-  [Acknowledgements and Resources](#Acknowledgements-and-Resources)

# About the Project
Aim of semantic segmentation is to accurately classify each pixel in an image into specific object or class categories, facilitating detailed scene understanding for various computer vision applications.

![Semantic Segmentation.png](https://github.com/extint/Semantic_Segmentation/raw/main/Assets/Images/Semantic_Segmentation.jpg)

## Inferences
| Model | Accuracy| Validation Accuracy|Epochs|Dataset|
|------ |--------|------|--|-----|
|  UNet | 27.39 | 22.36|5 |ADE20KChallengeData2016|
|SegNet | 39.80 | 30.17|10|ADE20KChallengeData2016|
|ERFNet|92.27|92.92|10|Aerial Imagery |
## Tech Stack
- [Python](https://www.python.org/)
- [Opencv](https://opencv.org/)
- [Numpy](https://numpy.org/doc/#)
- [Tensorflow](https://www.tensorflow.org/)
- [Pytorch](https://pytorch.org/)
for the model
## File Structure
```
📦 Semantic Segmentation 
 ┣ 📂Assets/Images                     # Contains images of the results and techniques
 ┣ 📂Dataset                           # Dataset 
 ┃ ┣ Dataset.md                        # Information about the dataset
 ┃ ┣ customize_dataset.py              # Use this while training it on custom datset
 ┣ 📂Implementation                     
 ┃ ┣ 📂Models                          # Information about models implemented from scratch
 ┃ ┃ ┣ 📂UNet
 ┃ ┃ ┣ UNet.md
 ┃ ┃ ┣ UNet.ipynb
 ┃ ┃ ┣ 📂ErfNet
 ┃ ┃ ┣ ErfNet.md
 ┃ ┃ ┣ ErfNet.ipynb
 ┃ ┃ ┣ 📂SegNet
 ┃ ┃ ┣ SegNetNet.md
 ┃ ┃ ┣ SegNet.ipynb
 ┃ ┃ ┣ 📂ShuffleNet                    #TheFinalarchitecture
 ┃ ┃ ┣ Architecture.md
 ┃ ┣ 📂Utils                            
 ┣ 📜README.md                         # About the project
 ┣ 📜project_report.docx               # Project Report
 ┗ 📜requirements.txt                  # Requirements
```

# Getting Started
## Prerequisites and installation
- Download Python on your device if not already present. 
 Refer [here](https://www.python.org/downloads/) for the setup.
- You can use any code editor.
- All installations mentioned are made using pip hence install pip.
- To install pip , follow this [link](https://www.geeksforgeeks.org/how-to-install-pip-on-windows/)
- To install the requirements 
```
pip install -r requirements.txt 
```

## Installation
- Clone the repository
```
git clone https://github.com/extint/Semantic_Segmentation.git
```
## Download the dataset
- Download the ADE20K scene parsing dataset:
```bash
chmod +x download_ADE20K.sh
./download_ADE20K.sh
```

# Theory and Approach
* We aim to use the **Convolutional Neural Network** approch over the traditional algorithms because CNNs can learn features automatically, work end-to-end, maintain spatial information, offer adaptability and transfer learning, and achieve state-of-the-art performance and hence are more effective and versatile for this task.
To know more about CNNs, go through [this document](https://github.com/Anoushka1009/Semantic_Segmentation/blob/d4b1e09b3fe3fc698ec354e0eeb075ec13a15f17/Implementation/Approach.md)

* Overview of the architecture used: 
The architecture we've chosen for real-time semantic segmentation is **MobileNetV2** because its efficiency is achieved through a combination of architectural innovations and design choices that reduce the model's computational complexity and memory footprint without sacrificing too much in terms of performance. It's an excellent choice for tasks like image classification, object detection, and more on mobile and embedded devices.
To learn more about the architecture used, click  [here](https://github.com/Anoushka1009/Semantic_Segmentation/blob/d4b1e09b3fe3fc698ec354e0eeb075ec13a15f17/Implementation/Architecture.md)

# Results and Demo
### Original 
![](https://github.com/extint/Semantic_Segmentation/raw/main/Assets/Images/vjti_studyspace_seg.gif)
### Segmented Output
![](https://github.com/extint/Semantic_Segmentation/raw/main/Assets/Images/vjti_studyspace.gif) 

# Future Work
* Working on deep learning based computer vision technique of landmark detection. 
* Exploring other applications of semantic segmentation like medical, satellite imagery videos, night-vision, etc.
* Implementation of MobileNet architecture completely from scratch
* Pruning and Optimisation of model for deployment on OAK-D camera.

# Contributors
- [Vedant Mehra](https://github.com/extint)
- [Abhi Mehta](https://github.com/MehtaAbhii) 
- [Anoushka Ruikar](https://github.com/Anoushka1009)

# Acknowledgements
 - [COC VJTI]() ProjectX 2023
 - Our mentors [Smit Shah](https://github.com/Smit1603) and [Yatharth Dedhia](https://github.com/YatharthDedhia) for their valuable mentorship throughout the project. 
 
# Resources
 - [A Comprehensive Guide to Convolutional Neural Networks](https://www.v7labs.com/blog/convolutional-neural-networks-guide)
 - [MobileNetV2: Inverted Residuals and Linear Bottlenecks](https://arxiv.org/abs/1801.04381)
 