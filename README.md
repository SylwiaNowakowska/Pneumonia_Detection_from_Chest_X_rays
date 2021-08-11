# ChestXNet: Pneumonia Detection from Chest X-rays with Convolutional Neural Networks

## Project info
This project is part of AI in healthcare course on Udacity Platform. <br>
https://www.udacity.com/course/ai-for-healthcare-nanodegree--nd320 <br>

The goal of the project is to classify the X-ray scans as pneumonia postive or negative. Different Convolutional Neural Network architectures based on DenseNet121 pre-trained model are built, trained and evaluated.

## Dataset info
The dataset used in this project: 

NIH Chest X-ray Dataset comprised of 112,120 X-ray images with disease labels from 30,805 unique patients.
The labels include 14 pathologies and were extracted using Natural Language Processing (NLP) from radiological reports. <br>
<br>
Detailed info: https://www.kaggle.com/nih-chest-xrays/data 

## Project files
 1. EDA (exploratory data analysis)
 2. Build and train model:
  &ensp; -  Processing metadata
  -  Creating training, validation and test datasets
  -  Comparison of demographic distributions in the training, validation and test datasets
  -  Building of different models, their training and evaluation
  -  Model performance summary
  -  Next steps
 3. Clinical workflow intergration
  - checking relevant DICOM matadata 
  - pre-processing image for the model
  - loading trained model and its weights
  - predicting the class
  4. FDA submission
  -  intended use statement
  -  indictaion for use
  -  device limitations
  -  clinical impact of performance
  -  algorithm architecture, training and validation description
  -  database used for algorithm development
  -  ground truth description


