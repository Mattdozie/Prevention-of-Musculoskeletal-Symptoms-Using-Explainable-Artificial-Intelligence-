### Table of Contents
- [Overview](#overview)
- [Motivation](#motivation)
- [Technical Aspect](#technical-aspect)
  1. [Exploratory Data Analysis](#exploratory-data-analysis)
  2. [Data Preprocessing](#data-preprocessing)
  3. [Model Selection and Implementation](#model-selection-and-implementation)
  4. [Performance Evaluation](#performance-evaluation)
  5. [Implementation and Adoption of Post-Hoc Explainable AI Techniques](#implementation-and-adoption-of-post-hoc-explainable-ai-techniques)
- [Installation](#installation)

## Overview
The rapid growth of Artificial Intelligence (AI) has led to the widespread adoption of opaque "black box" models across sectors. Despite their predictive prowess, concerns arise regarding accountability, justifiability, and compliance with regulations like GDPR, which protect individuals from decisions solely based on automated processing. To address this, there's a demand for algorithms capable of explaining AI predictions transparently. These algorithms aim to enhance understanding, accountability, and ethical use of AI, ensuring compliance with regulations while preserving individual rights and freedoms.

## Motivation
This project seeks the best-performing explainable AI model for occupational health and safety, targeting musculoskeletal disorder prevention. By addressing the black box challenge, it aims to foster trust and acceptance of AI across sensitive fields, paving the way for its widespread adoption in areas where transparency is paramount.

## Technical Aspect
1. **Exploratory Data Analysis**: The study employed descriptive and inferential statistics. Descriptive statistics summarized sample variables, offering insights into their characteristics. Inferential statistics examined variable relationships and inferred outcomes from sample analysis to the population. Regression and correlation techniques determined variable relationships.

<img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/509f0e5e-1b49-4473-9290-a48becee0ed2" alt="image" width="500">
<img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/9f99ef63-0819-4348-b2dd-20ba06d739b7" alt="image" width="500">

      .                                            
3. **Data Preprocessing**: The data preprocessing phase involved data cleaning to remove irrelevant data, detect and handle outliers, and address missing values. Univariate analysis showed normal distributions for weight, height, age, and BMI. Multivariate analysis revealed strong correlations between certain independent features and the dependent feature. Collinearity assessment showed no high collinearity among independent features. Data normalization was performed using standard scaling to ensure features had comparable weights. This prepared the data for training various machine learning models.

   
<img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/a9f30c74-647f-4947-8fca-1fb18b3040d7" alt="image" width="400">
<img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/3b5c80d0-07b0-4188-8379-c128382599b5" alt="image" width="400">


 [Dataset](Explainable AI Project Main Report.pdf)
  
6. **Model Selection and Implementation**: Model Selection and Implementation involved choosing machine learning algorithms suited for explainability and performance evaluation in occupational health and safety (OHS). Algorithms included Decision Trees (DT), Random Forest (RF), Gradient Boosting (GradBoost), LightGBM, CatBoost, XGBoost, and Artificial Neural Network (ANN). Hyperparameter tuning, dataset splitting, and algorithm-specific adjustments were applied to optimize model performance.
   
8. **Performance Evaluation**: Model performance in this study was evaluated using regression metrics such as RMSE, MSE, MAE, and R². Gradient Boosting Regressor and CatBoost Regressor showed the best performance in terms of RMSE, followed by Random Forest. CatBoost Regressor had the lowest MAE, indicating superior predictive accuracy compared to other models.

<div style="display: flex;">
  <img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/a0f49004-e42e-4d60-8baa-da4119f22571" alt="image1" width="500" style="margin-right: 10px;">
  <img src="https://github.com/Mattdozie/Prevention-of-Musculoskeletal-Symptoms-Using-Explainable-Artificial-Intelligence-/assets/100968289/c3002e24-e8cc-4086-a6d1-b543ff0f80b0" alt="image2" width="500">
</div>


10. **Implementation and Adoption of Post-Hoc Explainable AI Techniques**: The study implemented four post-hoc explainable AI techniques: LIME, SHAP, ASV, and PI, to interpret predictions of the Gradient Boosting Regressor model. Techniques provided both local and global explanations, assessing feature importance and model performance. The comparison revealed PI's clearer feature importance, enhancing user understanding despite SHAP's simpler visualizations.


The Project report can be viewed (<a href="Explainable AI Project Main Report.pdf">HERE</a>)

## Installation
Pandas, Numpy, Matplotlib, Seaborn, Scikit Learn, LIME, SHAP 


[Project Code](#)
