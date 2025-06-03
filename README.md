# README for Cyber-Attack Classification Project

## Project Overview
This project focuses on multiclass classification of cyber-attacks by analyzing network traffic data. The goal is to distinguish malicious traffic from legitimate traffic using machine learning and deep learning techniques. The dataset includes 9 types of cyber-attacks and a "Normal" class representing non-malicious traffic.

## Key Features
- **Data Analysis**: Comprehensive preprocessing including data cleaning, outlier handling, and feature engineering.
- **Machine Learning Models**: Implementation of SVM, Random Forest, and KNN.
- **Deep Learning Models**: Utilization of Feed-Forward Neural Networks, TabTransformer, and TabNet.
- **Performance Evaluation**: Models evaluated using accuracy, F1-score, precision, and recall metrics.

## Dataset
The dataset consists of 47 columns with network connection data, including:
- **Numerical and categorical variables**: Such as IP addresses, ports, protocols, and service types.
- **Target columns**: "Label" for binary classification and "Type" for multiclass classification (10 classes).

## Methodology
1. **Data Preprocessing**:
   - Handling missing values and duplicates.
   - Encoding categorical variables (One-Hot Encoding).
   - Balancing classes using techniques like SMOTE and undersampling.
   - Scaling and normalization (StandardScaler, MinMaxScaler, etc.).
   - Dimensionality reduction (PCA, LDA).

2. **Model Implementation**:
   - **Traditional ML**: SVM, Random Forest, KNN.
   - **Deep Learning**: Feed-Forward Neural Networks, TabTransformer, TabNet.

3. **Evaluation**:
   - Metrics: Accuracy, F1-score, precision, recall.
   - Confusion matrices for detailed class-wise performance.

## Results
- **Best Performing Model**: Feed-Forward Neural Network achieved an accuracy of 97.91%.
- **Detailed metrics** for each model and class are provided in the report.

## Dependencies
- Python 3.8+
- Libraries: pandas, numpy, scikit-learn, PyTorch, matplotlib, seaborn.

## Contributors
- Benedetta Bottari
- Milena Mazza

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For questions or collaborations, please contact the contributors via GitHub.

---

This README provides a concise overview of the project. For detailed information, refer to the full report in the `docs/` folder.
