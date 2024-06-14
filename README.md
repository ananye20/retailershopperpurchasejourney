# retailershopperpurchasejourney

## Overview

This project focuses on understanding and predicting the purchase journey of shoppers at a retailer's shop. It emphasizes extensive data wrangling, data preprocessing, and data visualization techniques, followed by machine learning modeling to predict customer loyalty. The models employed include Logistic Regression, Decision Trees, Random Forest, and K-Nearest Neighbors (K-NN).

## Dataset

The dataset used for this project contains information about the retailer's customers, including various features related to their shopping behavior and purchase patterns.

## Workflow

### Importing Libraries

Imported necessary libraries for data manipulation, preprocessing, visualization, and model building.

Before running the code, make sure to install the required packages by executing the following commands:

###### pip install numpy pandas matplotlib seaborn scikit-learn

### Data Preprocessing

Conducted extensive data preprocessing, including:
  - Data cleansing to handle missing values, outliers, and inconsistencies.
  - Feature engineering to create new variables and transform existing ones.
  - Techniques such as normalization, scaling, and encoding to prepare data for machine learning algorithms.

### Data Visualization

Visualized the preprocessed data to gain insights into customer behavior and purchase patterns.

### Scaling and Standardization

Applied scaling and standardization techniques to ensure uniformity in feature scales and distributions.

### Binarization

Employed binarization techniques for certain features to convert them into binary format for modeling purposes.

### Encoding Categorical Variables

Encoded categorical variables to convert them into numerical format for modeling.

### Fitting Models

Fitted the following machine learning models to predict customer loyalty:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - K-Nearest Neighbors (K-NN)

### Training Models

Trained the fitted models on the preprocessed data to learn patterns and relationships.

### Model Evaluation

Evaluated model performance using metrics such as accuracy, sensitivity, specificity, and F1 score. These metrics provide valuable insights to the retailer for strategic decision-making and enhancing customer retention strategies.

## Model Performance

| Model               | Accuracy | Sensitivity | Specificity |
|---------------------|----------|-------------|-------------|
| Logistic Regression | 0.837607 | 0.844701    | 0.817365    |
| Decision Trees      | 0.823621 | 0.845750    | 0.760479    |
| Random Forest       | 0.796426 | 0.927597    | 0.422156    |
| K-NN                | 0.775447 | 0.934942    | 0.320359    |

## Conclusion

This project showcases the application of various data preprocessing techniques and machine learning models to understand and predict the purchase journey of shoppers at a retailer's shop. By leveraging insights derived from the data, retailers can make informed decisions to enhance customer experiences and improve customer retention strategies.
