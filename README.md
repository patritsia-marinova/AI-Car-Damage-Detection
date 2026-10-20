# AI Car Damage Detection – Machine Learning for Insurance Claims

**Project Status: Work in Progress**

## Project Overview

During Semester 4 of my ICT studies at Fontys University of Applied Sciences, specialising in **AI & Machine Learning**, I started developing an AI-powered vehicle damage classification tool for the insurance industry.

The project is being developed as a potential start-up solution, with the Bulgarian insurance company **Bul Ins** as the intended first client.

The goal is to develop a machine learning model that identifies visible vehicle damage from photographs, potentially supporting insurance claims handlers during the initial assessment process.

Through domain research and an interview with Bul Ins, I identified several manual activities within the claims process, including data entry, document handling, and repeated information checks. This motivated me to explore how AI could support greater efficiency, although the specific business value of automated damage classification still requires further validation.

The current project focuses on **damage classification**, while repair cost estimation remains a possible future extension.

## Project Objectives

1. Understand the insurance claims process and identify opportunities for AI-supported automation.
2. Define the business problem, stakeholders, and data requirements.
3. Explore and prepare vehicle damage image datasets for classification.
4. Develop and compare machine learning models using k-NN and SVM.
5. Evaluate model performance, investigate misclassifications, and identify areas for improvement.
6. Work towards a reliable damage classification prototype.

## Methodology & Development

The project follows an iterative machine learning development approach.

### 1. Business & Domain Understanding

I started by researching the Bulgarian insurance industry and investigating Bul Ins's claims process.

I developed a project proposal, conducted a stakeholder interview, and defined the data requirements, including image quality, damage labels, class representation, and legal considerations.

### 2. Data Preparation & Initial Modelling

I explored the CarDD vehicle damage dataset and developed my first **k-Nearest Neighbors (k-NN)** classification model.

The initial model achieved **39.4% accuracy**. Following supervisor feedback, I introduced cropped damage images, improving accuracy to **45.7%**.

Further experiments highlighted the importance of class imbalance and reliable evaluation methods.

### 3. SVM Model Development

I developed a **Support Vector Machine (SVM)** classifier as an alternative to k-NN.

I compared models with and without balanced class weights and observed improved recognition of underrepresented damage categories when using class weighting.

### 4. Model Evaluation & Error Analysis

My current work focuses on understanding why the model makes incorrect predictions.

I am investigating confusion between damage categories, particularly dents and scratches, and exploring how image characteristics such as brightness, colourfulness, and image size may influence classification results.

Based on supervisor feedback, I am expanding the analysis with visualisations, class-specific comparisons, and closer inspection of misclassified images.

## Tools & Technologies

| Area | Tools & Methods |
|---|---|
| Programming & Data Analysis | Python, Pandas, NumPy, Jupyter Notebook |
| Machine Learning | Scikit-learn, k-NN, Support Vector Machines (SVM) |
| Data Preparation | Image preprocessing, cropping, dataset splitting |
| Data Visualisation | Matplotlib, Seaborn |
| Model Evaluation | Accuracy, Confusion Matrices, Class-wise Performance, Error Analysis |
| Business Analysis | Domain Research, Stakeholder Interviews, Data Requirements |

## My Contribution

This is an **individual project**, where I am responsible for the research, development, evaluation, and documentation.

My work includes:

- Conducting domain research and interviewing Bul Ins to understand the business environment.
- Defining project objectives, data requirements, and dataset selection criteria.
- Exploring and preparing vehicle damage images for machine learning.
- Developing and comparing k-NN and SVM classification models.
- Analysing model performance, class imbalance, and misclassifications.
- Applying supervisor feedback to improve the quality of my experiments and conclusions.

Through this project, I am developing practical experience in **machine learning, computer vision, data analysis, model evaluation, and translating business problems into AI solutions**.

## Repository Structure

| Folder | Contents |
|---|---|
| [**01 – Business & Domain Understanding**](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/tree/main/01%20%E2%80%93%20Business%20%26%20Domain%20Understanding) | Project proposal, insurance domain research, stakeholder interview, and data requirements |
| [**02 – Model Development & Iterations**](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/tree/main/02%20%E2%80%93%20Model%20Development%20%26%20Iterations) | k-NN baseline, preprocessing improvements, SVM development, and model comparisons |
| [**03 – Current Model & Error Analysis**](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/tree/main/03%20%E2%80%93%20Current%20Model%20%26%20Error%20Analysis) | Latest SVM notebook, misclassification investigation, and ongoing error analysis |

Each folder contains supporting evidence and documentation of the development process.

## Current Progress & Next Steps

The project is still under development. My current priority is to improve the interpretation and evaluation of the SVM model rather than focus only on increasing accuracy.

The next steps include:

1. Investigating misclassified images and differences between damage categories.
2. Adding box plots, distribution charts, and visual comparisons.
3. Exploring how dataset diversity influences model predictions.
4. Supporting conclusions with clearer statistical and visual evidence.
5. Evaluating potential model improvements based on the findings.
6. Continuing towards a functional prototype for damage classification.

## Project Outcome

So far, I have established the business context, defined the machine learning problem, prepared image data, and developed several classification models.

The experiments have demonstrated how **image preprocessing, class imbalance, and model selection** can influence classification performance.

More importantly, the project has helped me understand that developing a machine learning solution involves more than achieving high accuracy. It also requires investigating errors, understanding data limitations, evaluating results critically, and considering how the solution could support a real business process.

As the project continues, my goal is to build a more reliable and explainable damage classification model while strengthening my skills in **AI, Machine Learning, Computer Vision, and Business Analytics**.
