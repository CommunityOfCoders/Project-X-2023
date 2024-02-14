# Image Inpainting 

This comprehensive project combines various techniques for image inpainting . It includes Fast Marching Method (FMM) for image inpainting, and partial convolutions for image inpainting using Keras.

## Table of Contents

- [Image Inpainting using FMM](#image-inpainting-using-fmm)
  - [Description](#description-1)
  - [Usage](#usage-1)
  - [Dependencies](#dependencies-1)
- [Partial Convolutions for Image Inpainting](#partial-convolutions-for-image-inpainting)
  - [Description](#description-2)
  - [Usage](#usage-2)
  - [Dependencies](#dependencies-2)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Technologies Used

- **OpenCV**
- **NumPy**
- **Matplotlib**
- **Google Colaboratory (Colab)**
- **TensorFlow**
- **PyTorch**
- **Kaggle**
- **Weights and Biases (Wandb)**

## File Structure:

📦IMAGE-INPAINTING  
 ┣ 📂ASSETS  
 ┃ ┣ 📂IMAGES  
 ┃ ┃ ┣ 📜FMM_INPUT_IMAGE.jpg  
 ┃ ┃ ┗ 📜PCONV_INPUT_IMAGE.jpg  
 ┃ ┣ 📂MASKS  
 ┃ ┃ ┣ 📜FMM_INPUT_MASK.png  
 ┃ ┃ ┗ 📜PCONV_INPUT_MASK.png  
 ┃ ┣ 📜PROJECT_REPORT.pdf  
 ┃ ┗ 📂MINI-PROJECT  
 ┃   ┣ 📜LICENSE_PLATE_DETECTION.ipynb  
 ┃   ┣ 📜Readme.md  
 ┣ 📂RESULTS  
 ┃ ┣ 📂FMM  
 ┃ ┃ ┣ 📜Screencast from 08-11-23 04...webm  
 ┃ ┃ ┗ 📜output.png  
 ┃ ┗ 📂PARTIAL_CONVOLUTION  
 ┃   ┣ 📜PCONVRESULT.png  
 ┃   ┗ 📜Screencast from 08-11-23 04...webm  
 ┣ 📂SRC    
 ┃ ┣ 📂MODEL  
 ┃ ┃ ┣ 📜INPAINTING_MODEL.py  
 ┃ ┃ ┣ 📜PCON2D.py  
 ┃ ┃ ┣ 📜model_v2 (1).png  
 ┃ ┃ ┗ 📜trainedmodel (1).h5  
 ┃ ┣ 📜PYTHONSCRIPT.py  
 ┃ ┣ 📜MAIN.py  
 ┃ ┗ 📂NOTEBOOKS  
 ┃   ┣ 📜FMM_IMPLEMENTATION.ipynb  
 ┃   ┣ 📜LICENSE_PLATE_DETECTION.ipynb  
 ┃   ┣ 📜pconv-implementation (3).ipynb  
 ┣ 📜README.md  

## Image Inpainting:

### Aim

The aim of this Image Inpainting project is to provide a robust solution for digital image restoration and manipulation. Our goal is to develop an automated system that can detect and remove unwanted objects or defects in images, and seamlessly fill in the missing regions with plausible background content. This technology can be highly beneficial in the following domains:

- **Content Editing**: Assisting graphic designers and content creators to easily remove unwanted elements from images, saving time and effort in manual editing.
- **Privacy Preservation**: Automatically detecting and removing sensitive information or objects from images to protect privacy before sharing them on public platforms.
- **Cultural Heritage**: Restoring old or damaged photographs and artworks, preserving historical and cultural heritage with minimal human intervention.
- **Retail and Real Estate**: Enhancing product images or real estate photos by removing distracting elements, providing cleaner and more attractive visuals for potential customers.

By leveraging advanced machine learning algorithms and deep learning techniques, our project aims not only to enhance the visual aesthetics of images but also to contribute to the broader field of computer vision and image processing by addressing challenges related to context-aware scene understanding and reconstruction.


## Image Inpainting using FMM  

![FMM input and output for 1 pixel thick damaged portions](/RESULTS/FMM/fmm_output1.png)  

![FMM input and output for 2 pixel thick damaged portions](/RESULTS/FMM/fmm_output2.png)



### Description
This component of the project focuses on image inpainting using the Fast Marching Method (FMM). FMM is a powerful algorithm for filling in missing or damaged regions in images while preserving their structural and textural properties. But due to the absence of deep learning it cannot inpaint accurately for images having larger damaged portionsas seen in the given images ,thus leading to the need for incorporating deep learning in image inpainting. The code for this implementation can be found in the 'fmm_inpainting' directory.

### Usage
To use the FMM inpainting code:
1. Download and run PYTHONSCRIPT.py located in SRC
2. Give the paths of the image and binary mask as the inputs 
3. Choose option 1


### Dependencies
The FMM inpainting component relies on the following:
- Python
- Libraries used are Numpy,cv2,Matplotlib and Math


## Partial Convolutions for Image Inpainting
![Inpainting Results Using Partial Convolutions](/RESULTS/PARTIAL_CONVOLUTION/PCONVRESULT.png)

### Description
This component explores the use of partial convolutions for image inpainting using Keras. Partial convolutions are effective in preserving details during the inpainting process. The code for this implementation can be found in the 'partial_convolution' directory.

## Usage

To perform image inpainting using partial convolutions, follow these steps:
1. Download and run PYTHONSCRIPT.py located in SRC
2. Give the paths of the image and binary mask as the inputs 
3. Choose option 2


### Dependencies

The partial convolutions for image inpainting component rely on the following:
- Python
- Libraries used are Numpy,cv2,Matplotlib,Math,Tensorflow

## Future Work

Our future work will harness Generative Adversarial Networks (GANs) to elevate image inpainting, especially for images with extensive damage. GANs, with their innovative generative-discriminative interplay, hold the potential to craft detailed, context-aware fill-ins. We’ll focus on perfecting GANs for complex areas, enhancing texture blending and edge coherence where partial convolutions fall short.

We plan to tailor GANs for precise detail recovery in intricate or semantically significant regions. Our goal is a system that delivers seamless, undetectable inpainting across any image, which could revolutionize fields from art restoration to medical imaging. Integrating GANs represents a leap toward indistinguishable, realistic image reconstruction, propelling automated image restoration forward.

## Acknowledgments

We would like to express our gratitude for the tools and platforms that contributed to the success of this project:

- **Keras**: We leveraged the Keras deep learning framework for implementing partial convolutions in image inpainting.
- **Google Colab**: Google Colab provided a collaborative environment for the development of the FMM and object detection components. Its cloud-based Jupyter notebooks facilitated data processing and model training.
- **Kaggle**: Kaggle served as our platform of choice for collaborative work on the partial convolution part of the project. Its collaborative coding environment and version control features streamlined the development process.
- **Research Paper**: https://www.researchgate.net/publication/238183352_An_Image_Inpainting_Technique_Based_on_the_Fast_Marching_Method
- **Research Paper**: https://doi.org/10.48550/arXiv.1804.07723

## Contact

If you have any questions, need assistance, or wish to get in touch with us, please feel free to reach out to the authors:

- **Kindipsingh Mallhi**: [GitHub](https://github.com/kindipsingh)
- **Aditi Dhumal**: [GitHub](https://github.com/aditidhu)

