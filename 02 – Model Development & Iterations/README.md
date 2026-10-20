# 02 – Model Development & Iterations

## Overview

This folder contains the development and improvement of my machine learning models for the **AI Car Damage Detection** project.

The objective is to classify visible vehicle damage from photographs using supervised machine learning. I started with a **k-Nearest Neighbors (k-NN)** baseline and gradually improved the approach based on model results, data quality issues, and supervisor feedback.

I later explored **Support Vector Machines (SVM)** to compare model performance and investigate the effect of class imbalance.

## Activities & Evidence

### 1. [k-NN – Initial Baseline](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/blob/main/02%20%E2%80%93%20Model%20Development%20%26%20Iterations/Iteration0_Baseline%20(1).ipynb)

Developed my first k-NN classification model using the CarDD dataset.

I explored the dataset, examined the distribution of damage categories, prepared the images for classification, and evaluated the model using accuracy and a confusion matrix.

The initial model achieved **39.4% accuracy**, providing a baseline for further improvements.

### 2. [k-NN – Cropped Damage Images](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/blob/main/02%20%E2%80%93%20Model%20Development%20%26%20Iterations/Iteration0_Baseline%20(2).ipynb)

Following supervisor feedback, I changed the preprocessing approach to crop individual damage regions instead of resizing entire vehicle photographs.

This allowed the model to focus more directly on the damaged areas and improved accuracy to **45.7%**.

### 3. [k-NN – Further Iterations](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/blob/main/02%20%E2%80%93%20Model%20Development%20%26%20Iterations/Iteration0_Baseline%20(3).ipynb)

Continued experimenting with the k-NN model and investigated the influence of class imbalance on evaluation results.

I explored balancing the test set to obtain a more representative evaluation across damage categories. These experiments highlighted the importance of looking beyond overall accuracy when evaluating classification models.

### 4. [SVM – Model Development](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/blob/main/02%20%E2%80%93%20Model%20Development%20%26%20Iterations/SVM.ipynb)

Developed an SVM classification model as an alternative to k-NN.

I compared models with and without balanced class weights to investigate how underrepresented damage categories influence predictions.

Using balanced class weights improved the recognition of less frequent categories by assigning greater importance to classification errors involving those classes.

## Outcome

These iterations helped me understand how **data preparation, image preprocessing, class imbalance, and algorithm selection** influence machine learning performance.

By developing and comparing k-NN and SVM models, I gained practical experience in **Python, image classification, model evaluation, and iterative machine learning development**.

The project is still ongoing. My current work focuses on investigating misclassifications and understanding model behaviour through more detailed error analysis, documented in the next folder, **03 – Current Model & Error Analysis**.
