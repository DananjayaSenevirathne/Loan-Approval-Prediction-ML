# Bank Loan Risk Assessment & Prediction System
This repository contains the end-to-end Machine Learning implementation for the **5DATA002W.2 - Machine Learning & Data Mining** coursework. The project demonstrates the application of supervised learning techniques to solve real-world financial problems.

---

### Project Overview
The core objective of this project is to assist financial analysts in two specific domains:
1. **Loan Approval Classification (Case Study A):** Building robust models to predict whether a loan application should be approved or rejected.
2. **Loan Amount Regression (Case Study B):** Estimating the maximum loan amount that can be offered to approved clients, reducing financial risk.

### Key Technical Features
* **Data Pre-processing:** Extensive data cleaning including outlier detection (Age capping), missing value imputation (Median strategy), and encoding categorical variables.
* **Modelling:** * **Classification:** Implemented Naive Bayes, Logistic Regression, and K-Nearest Neighbors (KNN).
    * **Regression:** Built fully grown and pruned Decision Tree Regressors.
    * **Ensemble Learning:** Utilized Voting Classifiers to improve prediction accuracy and model stability.
* **Optimization:** Hyperparameter tuning using `GridSearchCV` to ensure optimal model performance and prevent overfitting.

###  Methodology

The workflow follows standard data mining practices:
1. **Data Profiling & EDA:** Visualizing target distributions and feature correlations.
2. **Model Training & Evaluation:** Using metrics like F1-Score, ROC-AUC (for classification), and MAE/RMSE (for regression).
3. **Justification:** Decisions are backed by statistical analysis and cited research.

---

###  Repository Structure
* `/notebooks`: Contains the Jupyter notebooks for Data Prep, Classification, and Ensemble/Regression tasks.
* `/data`: Pre-processed datasets (subsets for classification and regression).
* `requirements.txt`: Python dependencies.

### How to Run
1. Clone this repository: `git clone [repository-url]`
2. Upload the notebooks to Google Colab.
3. Place the dataset file in the root directory.
4. Execute cells sequentially.

---

###  Author
* **Name:** [Dananjaya Senevirathne]
* **Module:** 5DATA002W.2 - Machine Learning & Data Mining
* **Institution:** University of Westminster

---
*Disclaimer: This project is developed for educational purposes under the University of Westminster's Machine Learning & Data Mining module.*
