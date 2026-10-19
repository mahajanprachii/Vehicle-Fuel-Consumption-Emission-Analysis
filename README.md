# Vehicle CO₂ Emission Classification using PCA and SVM

## Overview

This project focuses on classifying vehicles into three CO₂ emission categories: **Low, Medium, and High** using **Principal Component Analysis (PCA)** and a **Support Vector Machine (SVM)**.

The dataset was first divided into **numerical and categorical features**. Standard scaling was applied to the numerical features, while categorical features were encoded using a categorical encoder. After preprocessing, **PCA was applied to reduce the number of features while retaining 95% of the variance**.

The PCA-transformed features were then used to create the **Low, Medium, and High** emission classes. After that, an **SVM with an RBF kernel** was trained for classification, as the RBF kernel is suitable for capturing non-linear relationships in the data.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- PCA
- Support Vector Machine (SVM)

## Results & Visualization

The SVM model was evaluated on the test data using **accuracy, confusion matrix, and classification report**.

For visualization, the first two principal components (**PC1 and PC2**) were used to create a 2D representation of the test data and the SVM decision regions.

**SVM Accuracy: <img width="241" height="27" alt="Screenshot 2026-10-19 at 4 40 56 PM" src="https://github.com/user-attachments/assets/c7d60153-e5a3-4b76-be99-3f804d286b9b" />

## Conclusion

### SVM Classification Visualization

<!-- Add your SVM visualization here -->

<img width="560" height="415" alt="Screenshot 2026-10-19 at 4 42 07 PM" src="https://github.com/user-attachments/assets/caacf560-e4ae-4676-96d4-232625c39a16" />



PCA reduced the dimensionality of the dataset while retaining **95% of the original variance**, and the RBF-based SVM was then used to classify the vehicles into Low, Medium, and High CO₂ emission categories. The final PC1–PC2 plot provides a simple **2D representation of the classification results**.
