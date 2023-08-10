# Project List

- [Transfomer From Scratch](#transformer-from-scratch)
- [Image Inpainting](#image-inpainting)
- [Text Style Transfer](#text-style-transfer)
- [3D reconstruction from single RGB image](#3d-reconstruction-from-single-rgb-image)
- [Image Super resolution](#image-super-resolution)
- [VisualFlow - No Code Algorithm Compiler](#visualflow---no-code-algorithm-compiler)
- [ChessAI - Advanced Chess Game with AI opponent](#chessai---advanced-chess-game-with-ai-opponent)
- [No-Code DL](#no-code-dl)
- [Healthcare Chatbot](#healthbuddy---your-ai-health-companion)
- [Semantic Segmentation](#semantic-segmentation)

## Transformer From Scratch

**Description** : This is a learning oriented project. Tranformers are the state of the art text processing models (Used as a base in all major Large Language Models (LLMs) such as GP T(ransformer) 1,2,3,4, Bard, Llama, Claude, etc). This project is an attempt to understand the transformer architecture and its working. The project is divided into 3 parts

- Start by learning the very basics of Standard neural networks, backpropagation, tuning and optimizations, etc.
- Then move to the basics of Processing sequential/text data using RNNs,LSTMs, understand their usecases, drawbacks and the need of transformers.
- Finally we understand the working of transformers and implement a `text-completion model` using it from scratch.

The final model we train will not be close to the current SoTA models (due to limited data and compute) but you'll gain a thorough understanding of the transformer architecture and its working so you can contribute to the real-world development and research of Transformer-based models in Open-source(which is huge! and only increasing) or otherwise.

**Pre-Requisites** : Strong Python and C++ programming.

**Resources** : [Sequence Models-Andrew NG](https://www.coursera.org/learn/nlp-sequence-models/), [Original Transformer Paper-Attenion is All you need](https://arxiv.org/abs/1706.03762), [Neural Networks-Andrej Karpathy](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ)

**Difficulty** : Medium

**Mentor** : Labib Asari, Soham Mulye

## Image Inpainting

**Description** : The Image Inpainting project offers a unique opportunity to dive deep into the realm of image processing and deep learning. Inpainting is the process of filling in missing or corrupted parts of an image, restoring its visual integrity. This project is divided into two exciting stages, where you’ll not only learn the fundamentals but also gain hands-on experience with both traditional and cutting-edge inpainting techniques.

Stage 1: Hands-on Implementation of OpenCV Inpainting Algorithm
FIrst things first since this is a computer vision project, knowledge of basics of computer vision is a must. Here you will be allowed to explore different computer vision techniques and are expected to complete tasks related to them. In this stage, you will explore the OpenCV library and implement traditional inpainting algorithms. You will grasp the underlying concepts and techniques, and apply them to restore images with missing portions. This stage serves as a strong foundation for understanding the core principles of inpainting.

Stage 2: Deep Learning Implementation of Image Inpainting
Building upon your knowledge from the first stage, you will dive into the exciting world of deep learning. You will design and implement a neural network for image inpainting using state-of-the-art techniques. This stage empowers you to leverage the power of artificial intelligence to produce visually appealing and contextually accurate inpainted images.

**Pre-requisite** : Python Programming (Some Computer Vision and Deep Learing knowledge is a plus)

**Resources** : [Image-Inpainting Paper](https://arxiv.org/pdf/2104.01431.pdf), [Edge-Connect](https://github.com/knazeri/edge-connect), [OpenCV-Inpainting tutorial](https://docs.opencv.org/3.4/df/d3d/tutorial_py_inpainting.html).

**Difficulty** : Medium

**Mentor** : Dhruvanshu, Om

## Text Style Transfer

**Description** : Text Style Transfer is a task of transferring the style of one text to another. For example, if we have a text in an informal style, we can transfer it to a formal style while preserving the context. These tasks is very useful in many applications such as machine translation, text summarization, etc.
In this project, we will be implementing a text style transfer model using the Transformer architecture. The exact style-combinations will be decided as we go along the project.
Example : https://quillbot.com/

**Pre-Requisites** : Strong Python programming, experience in NLP/Deep Learning is preferable.

**Resources** : [awesome-list for Text-Style-Transfer](https://github.com/jiangqn/Text-Style-Transfer), [StyleFormer](https://github.com/PrithivirajDamodaran/Styleformer)

**Difficulty** : Hard

**Mentor** : Labib Asari

## 3D reconstruction from single RGB image

**Description** : The "Three-Dimensional Reconstruction from a Single RGB Image" project focuses on the field of computer vision and 3D reconstruction. The goal of this project is to develop algorithms and techniques that can take a single RGB image as input and generate a plausible 3D representation of the scene depicted in the image. This involves extracting depth information, estimating the shape of objects, and creating a 3D model that closely resembles the original scene. Through the project, you will embark on an enriching learning journey. You will develop a strong grasp of fundamental deep learning principles, encompassing neural networks, loss functions, and optimization. The project will immerse you in diverse computer vision techniques, from image processing to depth estimation methods. Domains explored in the project would be Computer Vision, Machine Learning, Geometry and 3D Modeling, Image-to-Depth Conversion.

**Pre-Requisites** : Strong Python programming, experience in Deep Learning is preferable.

**Resources** : [Three-Dimensional Reconstruction from a Single RGB Image
Using Deep Learning](https://www.mdpi.com/2313-433X/8/9/225), [Pixel2Mesh](https://github.com/nywang16/Pixel2Mesh/tree/master)

**Difficulty** : Hard

**Mentor** : Soham Mulye

## Image Super Resolution

**Description** : Image super-resolution is a critical technique in the field of image processing that aims to enhance the quality and resolution of images, enabling them to exhibit finer details and improved visual fidelity. This process is particularly useful when dealing with low-resolution images that lack clarity and definition, often stemming from limitations in the image capture process or storage constraints.

The goal of image super-resolution is to generate a high-resolution version of an image from its low-resolution counterpart, effectively "upsampling" the image to a higher level of detail. This process involves predicting and inserting additional pixels into the low-resolution image to create a larger and more detailed version while maintaining the coherence and authenticity of the content.

Throughout this project, mentees will gain a comprehensive understanding of image super-resolution techniques, progressing from fundamental image manipulation using OpenCV to advanced deep learning models. They will learn to enhance image quality by exploring interpolation-based methods, upsampling techniques, and intricate deep learning architectures like CNNs and GANs. By implementing models such as SRGAN and ESRGAN from scratch, mentees will acquire hands-on experience in model development, training, and fine-tuning. This journey will equip them with the skills to transform low-resolution images into high-definition visual treasures, blending theoretical knowledge with practical expertise in image enhancement and deep learning.

**Pre-Requisites** : Strong Python programming and Deep Learning is preferrable.

**Resources** : [Neural Networks and Deep Learning](https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning), [Convolutional Neural Networks - Andrew Ng](https://www.coursera.org/learn/convolutional-neural-networks), [Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network](https://arxiv.org/abs/1609.04802)

**Difficulty** : Medium

**Mentor** : Om Doiphode

## VisualFlow - No Code Algorithm Compiler

**Description** : VisualFlow is a revolutionary project that transforms algorithm design into a seamless and intuitive process. By utilizing a drag-and-drop interface to construct algorithm flowcharts, this platform automatically generates code blocks and corresponding outputs. VisualFlow eliminates the need for traditional coding, enabling users to prototype, compile, and deploy algorithms effortlessly.

**Features** :

- **Intuitive Algorithm Design:** Construct complex algorithms by arranging and connecting visual nodes through an intuitive drag-and-drop interface.

- **Automatic Code Generation:** Seamlessly translate your visual flowcharts into executable code snippets in popular programming languages.

- **Effortless Testing:** Validate your algorithms promptly by simulating them directly within the visual flowchart interface.

- **Streamlined Collaboration:** Facilitate effective teamwork by sharing visual designs, enabling real-time collaboration.

**Pre-Requisites** :

- Proficiency in JavaScript, Python, or Java.
- Familiarity with web development technologies.
- Basic understanding of algorithm design principles.

**Resources** : [Prototype](https://drive.google.com/file/d/14XOqGd7501n6yqg8mClx46blVGA9j_5E/view), [Web](https://youtube.com/playlist?list=PLf7L7Kg8_FNzwwSK7c4Dei_h3oqg3dwYc), [React-Flow](https://reactflow.dev/docs/quickstart/), [Algorithms](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)

**Difficulty** : Hard

**Mentor**: Sameer Gupta

## ChessAI - Advanced Chess Game with AI opponent

 **Description** : ChessAI is an advanced chess game that offers players the opportunity to play against a highly intelligent AI opponent. The AI opponent utilizes the NegMax algorithm for move generation and evaluation. Additionally, a Genetic Algorithm is employed to enhance the AI's decision-making process, leading to more strategic and diverse gameplay.

**Features** :

- **User Interface and Gameplay:** Design an intuitive and visually appealing GUI for the chess game.
Provide options to choose AI difficulty levels and game modes (player vs. AI, player vs. player).
Highlight valid moves, check, and checkmate conditions.
Implement features like castling, en passant captures, and pawn promotion.

- **AI Part:** The project aims to initially implement the NegMax algorithm, optimizing move generation and evaluation for chess gameplay. Subsequently, the focus shifts to enhancing AI strategies through the integration of a Genetic Algorithm. This two-step approach ensures the development of a strong foundational AI before introducing evolutionary mechanisms for improved gameplay intelligence.

**Pre-Requisites** : Strong Python programming, experience in Pygame is preferable.

**Resources** : [Pygame](https://medium.com/iothincvit/pygame-for-beginners-234da7d3c56f)

**Difficulty** : Hard

**Mentor**: Siddheshsingh Tanwar

## No-Code DL

**Description** : The [No-Code DL project](https://github.com/sameergupta4873/no-code-DL) was started by your seniors to develop a platform that enables users to build deep learning models using a drag-and-drop feature without writing a single line of code. The project empowers users to leverage the power of deep learning to solve real-world problems, regardless of their programming experience.
The webapp consists of a user-friendly interface allowing them to design their model architecture using a drag-and-drop feature, chose datasets,hyperparametrs, etc. It currently supports Standard Neural Networks, Convolutional Neural Networks and basic Recurrent Neural Networks.
It also has a collboration feature that allows users to share their models with others,  work on them together in real-time and save different architectures as commits.

The aim of this project is to extend No-Code DL to 
- Improve the RNN support and add support for more complex models such as Transformers, GANs, etc.
- Develop a mechanism to allow users to upload their own datasets.
- Research and implement a mechanism to allow users to train their models on the cloud or locally.
- Design a mini-model to infer users problem and generate recommendations for model choices.
- [WebGPU](https://developer.mozilla.org/en-US/docs/Web/API/WebGPU_API) is recent development in the web world that allows us to use the GPU directly from the browser. Research on how No-Code DL can leverage this.

**Pre-Requisites** : Basic Web Development(NextJS and tailwind experience is a plus)  OR  Python(Basic Deep Learning Knowledge is a plus)

**Resources** : [No-Code DL source-code](https://github.com/sameergupta4873/no-code-DL) Go throught it understand the existing implementation, [NextJS](https://www.youtube.com/watch?v=wm5gMKuwSYk&pp=ygUGbmV4dGpz), [Deep Learning](https://d2l.ai/)

**Difficulty** : Medium

**Mentor** : Sameer Gupta, Labib Asari

## HealthBuddy - Your AI Health Companion

**Description** : The HealthBuddy Chatbot is an innovative and user-friendly healthcare solution designed to provide individuals with personalized and reliable healthcare information and support. This project aims to create a versatile chatbot that can offer assistance in various aspects of healthcare, including symptom diagnosis, mental health consultation, nutrition guidance, and more. The inspiration behind this project is to empower users to make informed healthcare decisions and promote overall well-being.

**Why are chatbots important in healthcare?**

According to a [research](https://link.springer.com/article/10.1007/s10916-019-1237-1) in 2019, the most valuable features of using chatbots in healthcare include:
- **Monitoring**: Awareness and tracking of user’s behavior, anxiety, and weight changes to encourage developing better habits.
- **Anonymity**: Especially in sensitive and mental health issues.
- **Personalization**: Level of personalization depends on the specific application. Some applications make use of measurements of:
   - Physical vitals (oxygenation, heart rhythm, body temperature) via mobile sensors.
   - Patient behavior via facial recognition.
- **Real time interaction**: Immediate response, notifications, and reminders.
- **Scalability**: Ability to react with numerous users at the same time

**Pre-Requisites** : 
- Proficiency in Python programming
- Familiar with ML

**Resources** : 
- [Transfomer architecture](https://towardsdatascience.com/illustrated-guide-to-transformers-step-by-step-explanation-f74876522bc0)
- [Attention is all you need](https://arxiv.org/pdf/1706.03762) paper that introduced the Transformer architecture, a neural network model for NLP tasks that relies solely on attention mechanisms to process input sequences.
- [NLP](https://www.coursera.org/specializations/natural-language-processing)


**Difficulty** : Medium

**Mentor** : Dishie Vinchhi, Om Doiphode

## Semantic Segmentation

**Description** : Semantic segmentation is a computer vision technique that involves partitioning an image into multiple segments, where each segment corresponds to a meaningful object or region within the image. The goal of semantic segmentation is to assign a specific label to each pixel in the image, indicating the category or class of the object or region that pixel belongs to.

In simpler terms, semantic segmentation aims to understand the content of an image at a pixel level by distinguishing and labeling different objects or areas. It is widely used in various applications, including autonomous driving, medical image analysis, object detection and recognition, scene understanding, and more.

Stage 1: Hands-on Implementation of OpenCV libraries and Semantic Segmentation On Images
In this initial project stage, the mentee will acquire essential skills in computer vision using OpenCV, grasp neural network basics, and delve into model optimization and pruning. Tasks include learning image processing with OpenCV, understanding neural network components, preprocessing a chosen dataset, building a basic CNN model for semantic segmentation, exploring model tuning and regularization, and gaining an introduction to model pruning techniques. This stage sets the groundwork for developing an efficient neural network model for image segmentation in subsequent stages.

Stage 2: Extending Stage 1 to video frames
Second stage of project will involve extending stage 1 of the project and implementing on video frames and testing for its efficiency with real-time speed. This part of project will involve extensive pruining of model and hence developing a better understanding and knowledge of neural networks.


**Pre-requisite** : Python Programming (Some Computer Vision and Deep Learing knowledge is a plus)

**Resources** :  [What Is Image Segmentation ?](https://www.v7labs.com/blog/image-segmentation-guide) - To understand Image Segmentation , [Semantic Segmentation Paper](https://sci-hub.se/https://doi.org/10.1109/IESPC.2019.8902391) - Just go through it,[Image Segmentation](https://github.com/ChinmayMundane/Image_segmentation) - Just go through readme and understand the basics of it

**Difficulty** : Medium

**Mentor** : Smit

