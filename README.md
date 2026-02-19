# glioma-classification
The purpose of this project is to compare supervised models (Random Forest, Logisitic Regression and Decision Tree) in determining Glioma grade between Lower Grade Glioma (LGG) and Glioblastoma Multiforme (GBM) as an efficient and accurate method to improve tumor treatment.

## Repo Structure
- data/ -> Contains dataset file
- Glioma Classification in Brain Tumors.ipynb -> Notebook

## Data Source
- The Cancer Genome Atlas (TCGA) Project that can be found on the The UC Irvine Machine Learning Repository (1)
- The dataset contains 839 patient records, and 23 variables on their clinical mutation information.
(1)Tasci, E., Camphausen, K., Krauze, A., & Zhuge, Y. (2022). Glioma Grading Clinical and Mutation Features [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5R62J.

## How to Run
1. Clone the Repo
2. Install required python packages
3. Open notebook in Jupyter


## Methods
- Data Loading and Cleaning
- Exploratory Data Analysis (EDA)
- Train-test split
- Model Training
    - Logistic Regression
    - Decision Tree
    - Random Forest
- Model Evaluation (ROC, AUC, Accuracy)
- Feature Importance

## Key Findings
- The Logistic Regression model achieved the best overall performance for Glioma Classification
- Mutations in the IDH1 protein are strongly associated with Grade 0 patients
- An older age at diagnosis are more strongly associated with Grade 1 patients

