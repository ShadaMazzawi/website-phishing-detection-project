# Website Phishing Detection Project

## Project Description

This project reproduces, evaluates, and critically analyzes the Kaggle notebook **"Website Phishing Detection ML Project"** by Duygu Jones. The objective is to classify websites as **phishing**, **suspicious**, or **legitimate** using machine learning techniques. In addition to reproducing the original work, the project extends the analysis with exploratory data analysis (EDA), feature engineering discussion, cross-validation, duplicate-row sensitivity analysis, feature importance analysis, and error analysis.

## Selected Article / Tutorial

Kaggle Notebook:
https://www.kaggle.com/code/duygujones/website-phishing-detection-ml-project

## Original GitHub Repository

https://github.com/Duygu-Jones/Phishing_Detection_ML_FastAPI_Docker

## Dataset Source

Kaggle Dataset:
https://www.kaggle.com/datasets/ahmednour/website-phishing-data-set

## Repository Contents

* `Website_Phishing_Final.ipynb` — Final Jupyter/Colab notebook.
* `Website_Phishing_Report_Final.pdf` — Final project report.

## Execution Instructions

1. Download the dataset from the Kaggle dataset link above.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Upload `Website Phishing.csv` when prompted.
4. Run all notebook cells from top to bottom.

## Main Models

* Logistic Regression
* Decision Tree
* Random Forest

## Main Findings

Random Forest achieved the strongest overall performance on the original dataset. Additional duplicate-row sensitivity analysis showed that removing exact duplicate rows reduced performance, indicating that duplicate records inflated the original evaluation results.
