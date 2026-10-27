# Comparative Analysis of Ensemble Learning Methods for Multi-Class Smartphone Addiction Classification Among Adolescents

## Project Overview

This project presents a comparative analysis of ensemble learning methods for multi-class smartphone addiction classification among adolescents. It investigates behavioral, psychological, and smartphone usage characteristics using supervised machine learning techniques.
The study evaluates three gradient boosting algorithms "XGBoost, LightGBM, and CatBoostL", against two conventional machine learning baselines, "K-Nearest Neighbors (KNN) and Support Vector Machine (SVM)".

The primary objective is to compare classification performance across four addiction severity categories and examine the challenges associated with imbalanced class distributions.

## Research Objectives

- Explore relationships between smartphone usage patterns, sleep duration, psychological indicators, and academic characteristics.
- Classify smartphone addiction severity into four categories: "Not Addicted, Low, Moderate, and High".
- Compare ensemble learning algorithms with conventional classification methods.
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Examine classification limitations, particularly for underrepresented classes.

## Dataset

**Dataset:** Teen Smartphone Usage and Addiction Impact Dataset

**Source:** [Kaggle — Teen Phone Addiction](https://www.kaggle.com/datasets/sumedh1507/teen-phone-addiction)

**Kaggle contributor:** sumedh1507

The dataset contains adolescent demographic, behavioral, psychological, and smartphone usage attributes, including daily screen time, sleep duration, phone-checking frequency, social media usage, self-esteem, depression indicators, family communication, and academic performance.

The dataset was obtained from Kaggle and was not independently collected as part of this project.

The four target categories were derived from the dataset's addiction-level scores using project-defined thresholds.

## Methodology

### 1. Exploratory Data Analysis

The analysis examines:

- Smartphone usage and addiction severity
- Sleep duration and addiction level
- Academic and demographic characteristics
- Age-related behavioral patterns
- Family communication and psychological indicators
- Feature correlations and usage distributions

### 2. Data Preprocessing

The original coursework includes categorical feature encoding, numerical feature scaling, feature selection, and stratified train-test splitting.

The preprocessing and evaluation pipeline requires further reproducibility verification.

### 3. Machine Learning Models

The following classifiers were investigated:

| Category | Algorithm |
|---|---|
| Ensemble Learning | XGBoost |
| Ensemble Learning | LightGBM |
| Ensemble Learning | CatBoost |
| Conventional Machine Learning | K-Nearest Neighbors (KNN) |
| Conventional Machine Learning | Support Vector Machine (SVM) |

### 4. Model Evaluation

Model performance was assessed using:

- Accuracy
- Precision and recall
- Class-specific F1-score
- Confusion matrices
- ROC-AUC

## Results

The original CSE427 project report presents the following model accuracies:

| Model | Reported Accuracy |
|---|---|
| LightGBM | 86.2% |
| XGBoost | 85.1% |
| CatBoost | 84.5% |
| SVM | 79.0% |
| KNN | 78.8% |


### Key Observations

- LightGBM achieved the highest overall reported accuracy.
- Gradient boosting classifiers outperformed the conventional baselines in the reported comparison.
- Performance varied substantially between addiction severity categories.
- Low and Not Addicted categories showed comparatively weak F1-scores, highlighting limitations in minority-class classification.

## Limitations

This project is an undergraduate comparative machine learning study, not a clinically validated smartphone addiction detection system.

The main limitations include:

- Weak classification performance for some minority classes.
- Potential sensitivity to class imbalance.
- The need to verify preprocessing and model evaluation consistency.
- Dependence on a third-party dataset and its original characteristics.
- Limited evidence for generalization beyond the dataset.
- Correlational findings do not establish causal relationships.

## Tools and Technologies

**Programming:** Python

**Data Analysis:** Pandas, NumPy

**Visualization:** Matplotlib, Seaborn

**Machine Learning:** scikit-learn, XGBoost, LightGBM, CatBoost

**Development Environment:** Google Colab

## Repository Contents

The repository contains:

- **Jupyter Notebook:** Exploratory analysis, preprocessing, machine learning experiments, and visualizations.
- **Project Report (PDF):** Academic documentation of the methodology, reported results, discussion, and references.

## Future Improvements

- Verify the preprocessing and evaluation pipeline.
- Improve reproducibility through consistent data splitting and preprocessing.
- Investigate class imbalance and minority-class performance.
- Explore model interpretability and feature importance.
- Evaluate the robustness and generalizability of model predictions.

## Academic Information

**Author:** Priota Das
**Institution:** BRAC University, Dhaka, Bangladesh
**Department:** Computer Science and Engineering
**Project Type:** Undergraduate Machine Learning Project

*This repository documents an academic coursework project. The results are presented for educational and portfolio purposes and should not be interpreted as clinical assessments of smartphone addiction.*
