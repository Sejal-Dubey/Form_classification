# Exercise_Form_classification

# Project Overview

This project focuses on Exercise Form Classification using computer vision techniques and machine learning models. The goal is to accurately classify whether an individual's exercise form is correct or incorrect using image or video input. The task lies under the domain of Digital Image Processing and serves as a practical application of classification algorithms in the AI-ML domain.

# Workflow of project 


![WhatsApp Image 2025-05-06 at 13 34 49_132821fe](https://github.com/user-attachments/assets/e141524c-af55-436a-a072-79d3b333c2d1)

The project's workflow is designed to automatically classify squat form correctness using image data. Here are the key steps involved: 

1. Image Collection: We captured images of individuals performing squats ourselves and manually labeled them based on form correctness. 

2. Data Preparation: The dataset has been prepared using different forms of squats to prepare training dataset by applying pre-processing. 
Description of dataset: 
This image dataset consists of a total of 40 images of both good and bad forms of squat exercise. 
Good Form: 20 images 
Bad Form: 20 images 

3. Image Preprocessing: Converted the RGB images to grayscale for simplifying analysis. Images were resized to 64x64 pixels, enhanced, and converted into text-based representations. We applied edge detection for region-of-interest identification and noise reduction. 

4. Feature Extraction: Utilized CountVectorizer to create bag-of-words representations. 

5. Model Training: We initialized and trained a Multinomial Naive Bayes classifier. 

6. User Interface (Streamlit App): Developed a user-friendly app for image uploads. 

7. Image Classification: For user-uploaded images, we: 

   Pre-process it. 

   Extract features and convert them into an array for futher classification. 

   Use the trained classifier to predict 'bad' or 'good' form. 

10. Result Display: The app displays 'Bad Form' or 'Good Form' based on the classifier's output. 

# Learning outcome

Understanding of Computer Vision: This project helped us gain a solid understanding of computer vision concepts and techniques, as well as familiarity with popular libraries like TensorFlow for implementing object detection. We learnt how to use the TensorFlow Object Detection API to train and deploy object detection models. 

Data Annotation and Preparation: We developed skills in annotating training data by labeling images with bounding boxes around key body parts and objects in the exercise scenes. By the end of this project, we will be able to analyze detected poses and forms to provide actionable insights to users about their exercise technique. 

Processing of images: We learnt and implemented digital images pre-processing steps and  passed those images to apply a classification model for classifying images and displaying results accordingly. 

Domain Knowledge: We acquired knowledge about essential steps involved in processing any image and then applying models as per the target to be achieved. Also exploring different models made us dive deeper in knowing their workflow  

Problem-Solving: This project honed our problem-solving skills as we encountered challenges related to model performance, data quality, and image processing, we learnt handling challenging scenarios, such as occlusions, unusual lighting conditions, and various body types, and find ways to make the model more robust. 

 

 
