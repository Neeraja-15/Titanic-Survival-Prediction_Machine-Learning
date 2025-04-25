# Machine-Learning_Project
# Titanic Survival Prediction - Machine Learning Assignment
### Overview
This project implements a machine learning pipeline to predict passenger survival using the Titanic dataset (train.csv from Kaggle). It covers Exploratory Data Analysis (EDA), data preprocessing, training a Logistic Regression model, and evaluating performance with metrics and visualizations. The deliverables include a Python script, a report, and visualizations, fulfilling the requirements of a machine learning assignment.
### Dataset

Source: Kaggle’s Titanic - Machine Learning from Disaster (train.csv).

Description: Contains 891 passenger records with features like age, sex, passenger class, and survival status.

Note: The script includes a fallback to an online source if train.csv is not locally available.

### Features

EDA: Visualizes distributions of age, survival, class, and sex.

Preprocessing: Handles missing values, encodes categorical variables, standardizes numerical features, and splits data (80-20).

Model: Logistic Regression for binary classification (survival prediction).

Evaluation: Computes accuracy, precision, recall, F1-score, and generates confusion matrix and ROC curve visualizations.

### Deliverables:

Python script (titanic_ml_assignment_final.py).

Report (ml_assignment_report.md).

Visualizations (eda_visualizations.png, confusion_matrix.png, roc_curve.png).



### Requirements

Python 3.8+

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Install dependencies:pip install pandas numpy matplotlib seaborn scikit-learn



### Setup

Clone the Repository:git clone https://github.com/Neeraja-15/titanic-Survival-Prediction-ml.git
cd titanic-Survival-Prediction-ml


### Download Dataset:

Get train.csv from Kaggle.

Place it in the project directory.

Alternatively, the script will fetch it from an online source if not found locally.


Install Dependencies:Run the pip command above to install required libraries.

### Usage

Run the Python script:python titanic_ml_assignment_final.py


### Outputs:
Console: Displays dataset info, missing values, and performance metrics.

#### Files:

ml_assignment_report.md: 2-3 page report summarizing the project.

eda_visualizations.png: EDA plots (age, survival, class, sex).

confusion_matrix.png: Confusion matrix for model predictions.

roc_curve.png: ROC curve with AUC score.




### Submission:
Create a ZIP file with:
titanic_ml_assignment_final.py
ml_assignment_report.md
Visualization PNGs (eda_visualizations.png, confusion_matrix.png, roc_curve.png)
Optionally, train.csv



### File Structure
titanic-ml-assignment/

├── titanic_ml_assignment_final.py  # Main Python script

├── ml_assignment_report.md         # Generated report

├── eda_visualizations.png          # EDA visualizations

├── confusion_matrix.png            # Confusion matrix

├── roc_curve.png                   # ROC curve

├── train.csv                       # Titanic dataset (optional)

└── README.md                       # This file

#### Notes

The script is well-commented for clarity and reproducibility.
Ensure train.csv is in the working directory or rely on the online fallback.
For alternative models (e.g., Random Forest) or additional features, modify the script as needed.

#### License
This project is for educational purposes and uses the Titanic dataset under Kaggle’s terms. Code is licensed under MIT License.
