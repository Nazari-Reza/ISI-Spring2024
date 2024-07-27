# ISI-Spring2024

This project was done by me for the statistical inference course in the spring of 2024 in University of Tehran

# README

## Project Title: Statistical Inference (Course Final Project)

### Author: Reza Nazari

### Institution: University of Tehran - Spring 2024

---

## Overview

This project focuses on statistical analysis and inference using a heart disease dataset. The analysis aims to uncover relationships and risk factors associated with heart disease, contributing to a better understanding of cardiovascular conditions. The dataset includes a variety of demographic, clinical, and diagnostic attributes.

---

## Contents

1. **Introduction**
2. **Data Attributes**
3. **Visualization and Summarization of Dataset Variables**
4. **Parametric Inference and Estimation**
   - T-Test
   - ANOVA Test
   - Chi-Square Test
   - Confidence Intervals
5. **Hypothesis Testing and Statistical Analysis**
   - Oldpeak and Slope Relationship
   - Age and Maximum Heart Rate Relationship
   - Thalassemia and Chest Pain Association
   - Cholesterol Levels and Exercise-Induced Angina
   - Gender and Heart Disease Association
   - Age and Resting Blood Pressure Relationship
6. **Additional Analysis**
   - Visualization Techniques
   - Critique of Analysis
   - Suggestions for Improvement

---

## Dataset Attributes

The dataset contains various attributes related to heart disease risk factors:

- **age**: Age of the patient (29-77 years)
- **sex**: Sex of the patient (1 = male, 0 = female)
- **cp**: Type of chest pain (1: typical angina, 2: atypical angina, 3: non-anginal pain, 4: asymptomatic)
- **trestbps**: Resting blood pressure (94-200 mm Hg)
- **chol**: Serum cholesterol level (126-564 mg/dl)
- **fbs**: Fasting blood sugar (> 120 mg/dl) (1 = true, 0 = false)
- **restecg**: Resting electrocardiographic results (0: normal, 1: ST-T wave abnormality, 2: left ventricular hypertrophy)
- **thalach**: Maximum heart rate achieved (71-202)
- **exang**: Exercise-induced angina (1 = yes, 0 = no)
- **oldpeak**: ST depression induced by exercise (0.0-6.2)
- **slope**: Slope of the peak exercise ST segment (1: upsloping, 2: flat, 3: downsloping)
- **ca**: Number of major vessels colored by fluoroscopy (0-3)
- **thal**: Thallium stress test result (3: normal, 6: fixed defect)
- **target**: Diagnosis of heart disease (0: < 50% diameter narrowing, 1: > 50% diameter narrowing)

---

## Key Analyses and Visualizations

1. **Sex-Based Differences in Heart Disease Frequency**
2. **QQ Plot Analysis of Thalach Distribution**
3. **Distribution of Oldpeak Values Across Different Slope Categories**
4. **Pairplot Analysis of Numerical Variables**
5. **Correlation Heatmap of Numerical Variables**

---

## Statistical Methods

### Parametric Inference

1. **T-Test**
   - Comparison of variables between disease and no disease groups.
2. **ANOVA Test**
   - Analysis of variance among groups.
3. **Chi-Square Test**
   - Association between categorical variables.

### Estimation Techniques

1. **Point and Maximum Likelihood Estimates**
2. **Goodness-of-Fit Analysis**
3. **Confidence Intervals**

---

## Hypothesis Testing and Regression Analysis

- **Oldpeak and Slope Relationship**
- **Age and Maximum Heart Rate Relationship**
- **Thalassemia and Chest Pain Association**
- **Cholesterol Levels and Exercise-Induced Angina**
- **Gender and Heart Disease Association**
- **Age and Resting Blood Pressure Relationship**

---

## Additional Sections

### Visualization

- Detailed visualizations to support the analysis.

### Criticism and Suggestions

- Critique.
- Suggestions for further analysis and improvement.

---

## Conclusion

This project provides a comprehensive statistical analysis of heart disease data, offering valuable insights into potential risk factors. The results can inform further research and contribute to improved diagnostic and treatment strategies in cardiovascular health.

---

## How to Use

1. **Clone the Repository**: `git clone <repository_url>`
2. **Install Dependencies**: Ensure you have Python and necessary libraries installed (e.g., pandas, matplotlib, seaborn, scipy).
3. **Run the Notebook**: Open `Statics.ipynb` in Jupyter Notebook and execute the cells to see the analysis.
4. **Read the Report**: The detailed analysis and findings are documented in `Report.pdf`.

---

## Contact

For any questions or further information, please contact nazarireza@ut.ac.ir.

---
