# Skin Disorder Prediction

## Introduction

The Skin Disorder Detection project aims to develop machine learning models to accurately classify various classes of skin diseases based on clinical and histopathological features. This README provides an overview of the project, including its objectives, dataset information, methodology, insights from exploratory data analysis (EDA) and classification models, as well as challenges faced during the project.

## Problem Statement

The primary objectives of the project are as follows:

1. **Task 1: Data Analysis Report**: Prepare a comprehensive data analysis report on the given dataset, focusing on understanding the features and patterns within the data.
   
2. **Task 2: Predictive Model**: Develop machine learning models using various techniques to predict different classes of skin diseases based on clinical and histopathological features.

3. **Task 3: Doctor Suggestions**: Provide recommendations to doctors for identifying skin diseases in patients at the earliest possible stage.

## Dataset Information

The dataset consists of 12 clinical attributes and 22 histopathological attributes, with a total of 34 attributes. It includes information on various skin diseases such as psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris. The dataset is anonymized and does not contain patient names or IDs.

## Attribute Information

### Clinical Attributes:

The clinical attributes include features such as erythema, scaling, definite borders, itching, koebner phenomenon, polygonal papules, follicular papules, oral mucosal involvement, knee and elbow involvement, scalp involvement, family history, and age.

### Histopathological Attributes:

The histopathological attributes include features such as melanin incontinence, eosinophils in the infiltrate, PNL infiltrate, fibrosis of the papillary dermis, exocytosis, acanthosis, hyperkeratosis, parakeratosis, clubbing of the rete ridges, elongation of the rete ridges, thinning of the suprapapillary epidermis, spongiform pustule, Munro microabscess, focal hypergranulosis, disappearance of the granular layer, vacuolization and damage of basal layer, spongiosis, saw-tooth appearance of rete ridges, follicular horn plug, perifollicular parakeratosis, inflammatory mononuclear infiltrate, and band-like infiltrate.

### Class of Diseases:

The dataset contains six classes of diseases: psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris.

## Methodology

The project methodology includes exploratory data analysis (EDA), feature engineering, data preprocessing, model selection, model training, model evaluation, and model interpretation. Various machine learning algorithms such as Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, Decision Tree, Gradient Boosting, XGBoost, Multinomial Naive Bayes, and Support Vector Classifier (SVC) were evaluated for their performance.

## Insights from EDA

EDA revealed insights into the distribution of clinical and histopathological features, familial transmission patterns of diseases, age distribution across different diseases, and correlations among features. The analysis provided valuable information for feature selection, data preprocessing, and model building.

## Insights from Classification Models

Several classification models were trained and evaluated using metrics such as accuracy score, classification report, and confusion matrix. Models like Logistic Regression, Gradient Boosting, and Support Vector Classifier showed promising results in terms of accuracy and generalization.

## Challenges Faced

Challenges encountered during the project included handling missing data, addressing feature imbalances, selecting appropriate evaluation metrics, and mitigating overfitting in some models. These challenges were addressed through careful preprocessing, feature engineering, model tuning, and evaluation.
