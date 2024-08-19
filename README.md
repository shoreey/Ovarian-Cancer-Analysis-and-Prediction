# Ovarian Cancer Analysis and Prediction

## Project Overview
This project focuses on analyzing and predicting surgical outcomes for ovarian cancer patients using machine learning techniques. The analysis includes data preprocessing, exploratory data analysis, feature engineering, and the application of various classification models.

## Dataset
The dataset contains various features related to ovarian cancer patients, including:
- Patient demographics
- Cancer characteristics (histology, grading, FIGO stage)
- Genetic information (BRCA status)
- Biomarkers (CA125, HE4, CA 15.3, CA 19.9, CEA)
- Treatment details
- Outcome information

## Key Features
1. Data Preprocessing
   - Handling missing values
   - Feature renaming for clarity
   - Encoding categorical variables

2. Exploratory Data Analysis
   - Analysis of missing data
   - Distribution of key features

3. Feature Engineering
   - Label encoding for categorical variables

4. Class Imbalance Handling
   - Implementation of SMOTE-Tomek technique

5. Model Development
   - Logistic Regression
   - Random Forest Classifier

## Methodology

### Data Preprocessing
- Renamed features from Italian to English for better understanding
- Analyzed and handled missing data
- Encoded categorical variables using Label Encoding

### Handling Class Imbalance
- Applied SMOTE-Tomek technique to balance the dataset
- Original class distribution: {0: 129, 1: 63}
- Balanced class distribution: {0: 129, 1: 129}

### Model Development and Evaluation

#### Logistic Regression
- Confusion Matrix:# Ovarian Cancer Analysis and Prediction

## Project Overview
This project focuses on analyzing and predicting surgical outcomes for ovarian cancer patients using machine learning techniques. The analysis includes data preprocessing, exploratory data analysis, feature engineering, and the application of various classification models.

## Dataset
The dataset contains various features related to ovarian cancer patients, including:
- Patient demographics
- Cancer characteristics (histology, grading, FIGO stage)
- Genetic information (BRCA status)
- Biomarkers (CA125, HE4, CA 15.3, CA 19.9, CEA)
- Treatment details
- Outcome information

## Key Features
1. Data Preprocessing
   - Handling missing values
   - Feature renaming for clarity
   - Encoding categorical variables

2. Exploratory Data Analysis
   - Analysis of missing data
   - Distribution of key features

3. Feature Engineering
   - Label encoding for categorical variables

4. Class Imbalance Handling
   - Implementation of SMOTE-Tomek technique

5. Model Development
   - Logistic Regression
   - Random Forest Classifier

## Methodology

### Data Preprocessing
- Renamed features from Italian to English for better understanding
- Analyzed and handled missing data
- Encoded categorical variables using Label Encoding

### Handling Class Imbalance
- Applied SMOTE-Tomek technique to balance the dataset
- Original class distribution: {0: 129, 1: 63}
- Balanced class distribution: {0: 129, 1: 129}

### Model Development and Evaluation

#### Logistic Regression
- Confusion Matrix:
# Ovarian Cancer Analysis and Prediction

## Project Overview
This project focuses on analyzing and predicting surgical outcomes for ovarian cancer patients using machine learning techniques. The analysis includes data preprocessing, exploratory data analysis, feature engineering, and the application of various classification models.

## Dataset
The dataset contains various features related to ovarian cancer patients, including:
- Patient demographics
- Cancer characteristics (histology, grading, FIGO stage)
- Genetic information (BRCA status)
- Biomarkers (CA125, HE4, CA 15.3, CA 19.9, CEA)
- Treatment details
- Outcome information

## Key Features
1. Data Preprocessing
   - Handling missing values
   - Feature renaming for clarity
   - Encoding categorical variables

2. Exploratory Data Analysis
   - Analysis of missing data
   - Distribution of key features

3. Feature Engineering
   - Label encoding for categorical variables

4. Class Imbalance Handling
   - Implementation of SMOTE-Tomek technique

5. Model Development
   - Logistic Regression
   - Random Forest Classifier

## Methodology

### Data Preprocessing
- Renamed features from Italian to English for better understanding
- Analyzed and handled missing data
- Encoded categorical variables using Label Encoding

### Handling Class Imbalance
- Applied SMOTE-Tomek technique to balance the dataset
- Original class distribution: {0: 129, 1: 63}
- Balanced class distribution: {0: 129, 1: 129}

### Model Development and Evaluation

#### Logistic Regression
- Confusion Matrix:

[[42 0]
[ 0 36]]
- Classification Report:
          precision    recall  f1-score   support
       0       1.00      1.00      1.00        42
       1       1.00      1.00      1.00        36
accuracy                           1.00        78


#### Random Forest Classifier
- Confusion Matrix:
[[42 0]
[ 0 36]]
- Classification Report:
          precision    recall  f1-score   support
       0       1.00      1.00      1.00        42
       1       1.00      1.00      1.00        36
accuracy                           1.00        78



## Results
Both Logistic Regression and Random Forest Classifier achieved perfect accuracy on the test set, indicating excellent predictive performance for surgical outcomes in ovarian cancer patients.

## Technologies Used
- Python
- Pandas for data manipulation
- Scikit-learn for machine learning models
- Imbalanced-learn for handling class imbalance

## Future Work
- Explore more advanced models like XGBoost or Neural Networks
- Perform feature importance analysis
- Conduct cross-validation for more robust performance evaluation
- Investigate the impact of different sampling techniques on model performance


This project demonstrates the application of machine learning techniques in predicting surgical outcomes for ovarian cancer patients, potentially aiding in treatment planning and patient care.




