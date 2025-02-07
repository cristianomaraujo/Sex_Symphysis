# AI-Based Sex Classification Using Mandibular Symphysis Measurements in Cephalometric Imaging

## Overview  
This repository contains the code used for developing machine learning models to predict sex based on the height and width of the mandibular symphysis in two-dimensional lateral cephalometric radiographs. This study aims to contribute to forensic anthropology by providing an AI-based approach for sex classification.

## Authors  
- Aline Xavier Ferraz  
- Pedro Felipe de Jesus Freitas  
- Bianca Marques de Mattos de Araujo  
- Erika Calvano Küchler  
- Odilon Guariza-Filho  
- Karinna Verissimo Taveira  
- Flares Baratto-Filho  
- Rosane Sampaio Santos  
- Angela Graciela Deliga Schroder  
- Cristiano Miranda de Araujo (Corresponding Author)

## Abstract  
**Objective:** This study aimed to develop machine learning-based predictive models for sex classification using mandibular symphysis height and width from lateral cephalometric images.  

**Methods:**  
- Dataset: 495 patients who underwent lateral cephalometric radiography.  
- Machine Learning Models: Logistic Regression, Gradient Boosting, K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Multilayer Perceptron (MLP), Decision Tree, AdaBoost, and Random Forest.  
- Model optimization: Hyperparameter tuning with Grid Search.  
- Validation: 5-fold cross-validation.  
- Performance Metrics: AUC, precision, recall, F1-score with confidence intervals estimated via bootstrapping.  

**Results:**  
- The models achieved AUC values ranging from **0.77 (95% CI: 0.70–0.82)** to **0.57 (95% CI: 0.50–0.65)** in testing and from **0.83 (95% CI: 0.80–0.87)** to **0.67 (95% CI: 0.63–0.75)** in cross-validation.  
- SVM, KNN, and Gradient Boosting models exhibited the highest predictive performance.  

**Conclusion:**  
Machine learning models successfully classified sex based on mandibular symphysis measurements, showing potential as a forensic anthropology tool. Future research should validate these models in different populations to ensure generalizability.

## Dataset  
The dataset used in this study consists of anonymized cephalometric measurements. Due to ethical considerations, only aggregated results and trained models are available in this repository.
