# Home Loan Prediction using Support Vector Machines (SVM)

## Introduction
This project explores the application of Support Vector Machines (SVM) for home loan prediction, focusing on two different kernel functions: linear and radial basis function (RBF). SVM is a powerful class of machine learning algorithms known for their effectiveness in classification tasks. Through this analysis, we aim to evaluate the performance of SVM models in predicting whether a home loan application will be approved or denied.

## About The Dataset
The dataset contains information about past loan applicants, including features such as income, credit score, loan amount, debt-to-income ratio, and employment duration. The target variable is binary, indicating whether the loan was approved (1) or not (0).

## Data Preprocessing
The dataset is preprocessed to handle missing values and encode categorical variables. Numerical variables are imputed with mean values, while categorical variables are imputed with the most frequent value. The data is then split into training and testing sets.

## SVM Models
### SVM with Linear Kernel
The SVM model with a linear kernel achieves an accuracy of 100%, indicating excellent performance. Precision, recall, and F1-score are also high, demonstrating robust classification capabilities.

### SVM with RBF Kernel
The SVM model with an RBF kernel achieves an accuracy of approximately 98.6%. Precision, recall, and F1-score are also high, indicating strong performance.

## Visual Representation
Contour plots are created to visualize the decision boundary of the SVM models with different kernels, providing insights into how they classify the data.

## Conclusion
In conclusion, this project provides insights into the application of SVM for home loan prediction using two different kernel functions. The SVM model with a linear kernel demonstrates excellent performance, while the RBF kernel offers flexibility in capturing intricate patterns in the data. The choice between these kernels depends on the dataset's nature and complexity. This analysis contributes to the understanding of SVM's effectiveness in risk assessment and loan approval tasks in the financial industry.
