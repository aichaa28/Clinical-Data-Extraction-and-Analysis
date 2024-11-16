# Clinical Data Extraction and Harmonization Project

This project involves the extraction, cleaning, and harmonization of clinical datasets, followed by an enhancement of predictive models using manually labeled data. The aim is to standardize clinical data for large-scale analysis and to improve predictive modeling techniques in the healthcare domain.


## Project Overview

### Objectives:
This project focuses on clinical data, specifically involving cancer-related information. The goal is to clean, extract, and harmonize raw clinical data from multiple sources, creating a standardized dataset. This dataset can then be used for large-scale analysis or as input for machine learning models.

The project is divided into two main tasks:
1. **Task 1:** Extracting and harmonizing the clinical data, including fields like age, sex, cancer type, tumour subtype, stage, and grade.
2. **Task 2:** Enhancing predictive models by leveraging labeled data for improving model accuracy in predicting clinical outcomes.

### Structure of the Project:
- **Task 1: Extraction and Harmonization:** Focuses on cleaning and standardizing clinical data fields to create a harmonized dataset.
- **Task 2: Enhancing Predictive Models:** Uses labeled data to build and improve machine learning models, applying techniques such as feature engineering and model selection.

## Task 1: Extraction and Harmonization of Clinical Data

### Objective:
To extract and standardize key pieces of information from the provided datasets to create a consistent and harmonized dataset that is suitable for further analysis.

### Requirements:
For each dataset in the folder, extract and clean the following information:
- **Age:** Convert age data into integers representing the patient's age in years.
- **Sex:** Standardize sex/gender data to one of the following strings: "Male", "Female", or "NA" if not available.
- **Stage and Grade:** Standardize cancer stage and grade information to Roman numerals: NA, "I", "II", "III", or "IV".
- **Cancer Type:** Standardize to strings like "Ovarian Cancer", "Breast Cancer", etc.
- **Sample Type:** Standardize to strings like "normal", "primary tumour".
- **Tumour Subtype:** Standardize to strings like "serous", "endometrioid", "mucinous", etc.


- **Code:** The code used for data extraction and harmonization is included in the Jupyter Notebook `Extraction&Harmonization.ipynb`.
- **Documentation:** Detailed explanations of the approach are included within the PDF document or the notebook as comments and markdown cells.

## Task 2: Enhancing Predictive Models with Labeled Data

### Objective:
To leverage manually labeled data to enhance predictive models, improving the extraction and harmonization process. The goal is to apply machine learning techniques to refine the model's output and improve the prediction accuracy.

### Requirements:
1. **Data Processing:** Methods to clean and prepare the labeled data.
2. **Feature Engineering:** Create new features from the labeled data that can enhance model performance.
3. **Feature Selection:** Identify the most relevant features to improve the model’s efficiency and effectiveness.
4. **Model Selection:** Choose suitable machine learning algorithms (e.g., decision trees, random forest, logistic regression) based on the dataset.
5. **Evaluation Methods:** Define evaluation metrics (e.g., accuracy, precision, recall) to assess model performance.


- **Code:** The data processing, feature engineering, model training, and evaluation are implemented in the Jupyter Notebook `Model_Enhancement.ipynb`.
- **Documentation:** An explanation of the methods and rationale for the approach is provided within the PDF document.


