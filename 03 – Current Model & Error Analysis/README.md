
# 03 – Current Model & Error Analysis

## Overview

This folder contains the latest working version of my **AI Car Damage Detection** model, focusing on SVM classification and error analysis.

After comparing k-NN and SVM models, I continued investigating how the model makes predictions and why certain damage categories are incorrectly classified.

The current focus is on **understanding model behaviour, identifying patterns in misclassifications, and supporting conclusions with evidence**, rather than simply improving overall accuracy.

**Project Status: Work in Progress**

## Activities & Evidence

### 1. [SVM – Model Evaluation & Error Analysis](https://github.com/patritsia-marinova/AI-Car-Damage-Detection/blob/main/03%20%E2%80%93%20Current%20Model%20%26%20Error%20Analysis/SVM-With%20error%20analysis.ipynb)

Continued developing my SVM model by investigating classification errors and comparing the characteristics of correctly and incorrectly classified images.

My analysis focuses on:

- **Confusion Matrix:** Identifying which damage categories the model frequently confuses, particularly dents and scratches.
- **Image Characteristics:** Investigating whether image size, brightness, and colourfulness influence misclassifications.
- **Class-Specific Performance:** Understanding why certain damage categories are more difficult to recognise.
- **Model Interpretation:** Exploring possible explanations for prediction errors instead of relying only on overall accuracy.

Following feedback from my supervisors, I am improving the analysis by including more visualisations and examining differences between damage categories.

## Current Improvements & Next Steps

Based on feedback from Bas and Hans, my next steps are:

1. Add box plots and distribution charts to better understand differences in image characteristics.
2. Visually inspect misclassified images alongside their true and predicted labels.
3. Investigate why the model frequently confuses dents and scratches.
4. Analyse damage categories separately to identify category-specific patterns.
5. Investigate dataset diversity, including differences in vehicle colours, shapes, and materials.
6. Support conclusions with statistical evidence and visualisations before making further model improvements.

## Current Outcome

This stage is helping me develop a deeper understanding of **machine learning evaluation, error analysis, and model interpretability**.

Rather than focusing only on improving accuracy, I am learning to investigate why a model makes certain mistakes and how dataset characteristics may influence its predictions.

The analysis is still ongoing, and the notebook will continue to be updated as I investigate misclassifications and apply supervisor feedback.
