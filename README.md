# Predicting Acute Compartment Syndrome Risk

This repository contains code and notebooks related to the analysis of acute compartment syndrome (ACS) risk prediction using the National Trauma Data Bank (NTDB). The project explores various aspects, including patient demographics, fracture locations, and machine learning techniques for predicting ACS outcomes.

### Authors: Frances Koback, on work for ACS project with Dr. Marmor at UCSF, in collaboration with Vivian Kwok, Safa Herfat, and Amrisha Maharaj 

#### Original Code:
##### Overview:
The original code comprises scripts and notebooks used for data preprocessing, exploratory data analysis (EDA), and initial modeling. It includes:

#### Data Preparation:

- Loading and cleaning the NTDB dataset.
- Mapping ICD-10 fracture diagnoses to anatomical locations.
- Exploratory Data Analysis (EDA):

####  Analyzing demographic patterns and fracture associations.
- Visualizations for missed ACS diagnoses and fasciotomy occurrences.
### Machine Learning Models:

- Implementation of Gradient Boosting models for ACS risk prediction.
- Evaluation metrics and feature importance analysis.
##### Usage:

- Run the notebooks in the provided sequence for a step-by-step analysis.
- Ensure necessary dependencies (libraries, packages) are installed.
#### AutoML Code Notebooks:
##### Overview:
###### The AutoML notebooks focus on using H2O's AutoML framework for enhanced model selection and evaluation. It includes:

#### Data Preparation:

- Selecting relevant columns for fractures and demographics.
- Converting categorical variables for H2O compatibility.

#### AutoML Modeling:

- Utilized H2O's AutoML to train models for ACS prediction.
- Evaluated model performance and extracted variable importances
- Analyzed key findings from AutoML models.
- Compared results with the initial Gradient Boosting models.

#### Usage:
Run the AutoML notebooks after completing the original code notebooks.
Adjust parameters such as runtime and model selection in AutoML for customization.

#### Requirements: 

- Python (3.10.9) 
- Jupyter Notebooks 
- Necessary libraries noted in the notebooks themselves 
- References:

List any external datasets, libraries, or tools used.

## Credits
All code contained in these folders is my own, please cite Frances Koback (frances.l.koback.med@dartmouth.edu) 


