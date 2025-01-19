# X Education Lead Scoring Model

## Problem Statement
X Education, an online course provider for industry professionals, is struggling with a low lead conversion rate. Although the company generates many leads daily, only about 30% of them are converted into paying customers. To improve this process, the company wants to identify the most promising leads, or "Hot Leads," who are more likely to convert. The goal is to build a model that assigns a lead score between 0 and 100 to each lead, helping the sales team focus on the leads with the highest conversion potential.

## Files Included

### 1. **Assignment Subjective Questions**
This document answers all the subjective questions posed by the company, detailing the assumptions made, the methodology used, and key insights from the analysis.

### 2. **Assignment Summary**
This document provides a concise summary of the entire approach, including methodology, key findings, and the results of the lead scoring model.

### 3. **Lead Case Study file.ipynb**
A Jupyter notebook containing the entire Python code for this project. It covers the following steps:
- **Data Loading and Preprocessing**: Includes loading the data, handling missing values, and encoding categorical features.
- **Feature Engineering**: Scaling, handling categorical variables, and PCA for dimensionality reduction.
- **Model Building**: Training a logistic regression model to assign lead scores.
- **Model Evaluation**: Calculating metrics such as accuracy, precision, recall, ROC-AUC, and confusion matrix.
- **Visualizations**: Heatmaps, ROC curves, and other plots to analyze model performance.

### 4. **Lead Score Case Study PPT**
A PowerPoint presentation summarizing the methodology, key findings, business recommendations, and model performance. This is useful for presenting the analysis to business stakeholders.

## Requirements

To run the `Lead Case Study file.ipynb` notebook, ensure the following libraries are installed:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels

