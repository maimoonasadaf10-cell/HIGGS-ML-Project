# HIGGS Boson Classification Using Machine Learning

## Project Overview
This project focuses on classifying particle collision events as either Higgs Boson signal events or background events using supervised machine learning techniques. The HIGGS dataset from the UCI Machine Learning Repository is used for model development and evaluation.

## Dataset
- Dataset: HIGGS Dataset
- Source: UCI Machine Learning Repository
- Total Instances: 11 Million
- Features: 28 numerical features
- Target Variable:
  - 1 = Higgs Boson Signal
  - 0 = Background Event

## Objectives
- Perform Exploratory Data Analysis (EDA)
- Preprocess and clean the dataset
- Train machine learning classification models
- Evaluate model performance
- Compare results using different metrics

## Data Preprocessing
- Dataset loading and inspection
- Feature renaming
- Train-Test splitting
- Feature scaling using StandardScaler
- Data visualization and analysis

## Exploratory Data Analysis
The following analyses were performed:
- Class Distribution Plot
- Histograms of Features
- Correlation Heatmap
- Boxplots for Outlier Detection

## Machine Learning Models Used
1. Logistic Regression
2. Random Forest Classifier
3. Support Vector Machine (SVM)

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## Results
The machine learning models successfully classified particle collision events into signal and background categories. Model performance was compared using classification metrics and visualizations.

## Project Structure
```
HIGGS-ML-Project/
│
├── HIGGS_18.ipynb
├── README.md
└── Report.pdf
```

## Author
**Maimoona Sadaf**  
B.E. Robotics and Artificial Intelligence  
JNNCE, Shivamogga

## References
- UCI Machine Learning Repository: HIGGS Dataset
- Baldi, P., Sadowski, P., & Whiteson, D. (2014)
- Scikit-Learn Documentation
