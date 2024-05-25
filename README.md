# Distinct Animals Detection Using YOLOv8 and Chatbot

## Overview 

Recognizing endangered animals plays a crucial role in biodiversity conservation. Identifying and assessing the potential threat levels leading to extinction of wild species is essential. Our team has chosen this topic to contribute to biodiversity protection, ecosystem balance, and sustainable development.

## Benefits of Endangered Animal Recognition 
   Recognizing endangered animals brings practical benefits in various fields:

   - Biodiversity Conservation

   - Support for Scientific Research

   - Community Awareness

   - Policy Planning Support

   - Ecotourism Development


## Main Objectives
- Train the YOLOv8 model on a diverse dataset of wildlife images with detailed annotations.
- Evaluate the model's performance on an independent test dataset.
- Deploy the system on mobile devices or computers with a user-friendly interface.
- Apply the system to real conservation projects.
- Develop an efficient and accurate endangered animal detection system using YOLOv8.

## Research Subjects

The main research subjects include:
- Endangered wildlife species in the research area.
- Images and videos of endangered wildlife species.
- Accompanying data with images and videos.

## Dataset


### Data Sources
- Public databases: iNaturalist, Wikimedia, Gbif, Wildlife Insights, Kaggle, Instagram, Facebook, Tiktok, Youtube, etc.
- Photographers' contributions.
- Data augmentation and video cropping to supplement the dataset.
- Citizen science platforms:
  - eBird
  - MammalWeb
  - HerpMapper
  - iNaturalist Research
- Data repositories:
  - Movebank
  - Panoptes
  - Global Biodiversity Information Facility (GBIF)
- Commercial data sources:
  - Getty Images, Shutterstock, Alamy
- Additional data:
  - Collection of data: Use of camera traps, unmanned aerial vehicles, or other data collection devices to gather wildlife images and videos in natural environments.
  - Data Augmentation
  - Video cropping: Divide long videos into shorter segments to generate more training data.

### Data Preprocessing

Before training the animal detection machine learning model, preprocessing steps are applied to standardize and enhance the dataset:

- Image Resizing
  - Purpose: Ensure uniform input size for the model.
  - Implementation: Use libraries like OpenCV to resize images, maintaining aspect ratio.

- Image Enhancement:
  - Purpose: Improve image quality for better feature extraction.
  - Techniques: Noise removal, brightness/contrast adjustment, color correction.
  - Implementation: Apply these techniques using image processing libraries.

- Data Augmentation:
  - Purpose: Increase dataset size for better model training.
  - Techniques: Rotation, flipping, cropping, brightness adjustment.
  - Implementation: Use libraries to apply augmentation, adjusting parameters for diverse data.

### Environment Setup:

- Training Environment:

Tool: Visual Studio Code
Usage: Used for training the model.
Model: Utilizes TensorFlow for model training.
Model Initialization:

- Data Preparation:
Gathered 8353 labeled images representing 12 endangered animal species.
Preprocessing:
Standardized and preprocessed images using libraries like Pandas, NumPy, Matplotlib, and TensorFlow.
Model Configuration:
Created a TensorFlow dataset containing the prepared images for training.
Listed and displayed the endangered wildlife species during the training process.
Model Execution:

- Training Data:
Utilized test and validation datasets containing prepared images for model training.
Model Building:
Employed the ultralytics library to construct the YOLOv8s model.
- Training:
Trained the model with epochs exceeding 200 and a batch size of 16, monitoring performance and loss metrics.
Conducted interrupted training over multiple days to allow for model adjustments if necessary.
