# Credit-Card-Fraud-Detection

**Objective:** The project focuses on detecting credit card fraud early using machine learning techniques, specifically LSTM neural networks and SMOTE for handling class imbalance.

**Problem Statement:** Credit card fraud poses significant financial risks to individuals and institutions. Early detection is crucial to minimize losses and ensure security.

**Methodology:**

**Dataset:** Utilized a credit card fraud dataset containing transactions with 22 features after preprocessing.
Preprocessing: Scaled 'Amount' and 'Time' features, filled missing values with column means, and applied SMOTE to handle class imbalance.
Modeling: Implemented an LSTM neural network architecture for sequence modeling due to its ability to capture temporal dependencies in data.
Evaluation: Trained the model on a resampled dataset, evaluated performance metrics such as accuracy, precision, recall, and F1-score using confusion matrix and classification report.

**Results:**
Achieved high accuracy and robust performance with LSTM, demonstrating its efficacy in detecting fraudulent transactions.
Utilized visualization tools to showcase training and validation metrics over epochs, highlighting model learning and performance trends.
**Impact:** The project contributes to financial security by leveraging advanced machine learning techniques to detect and prevent credit card fraud in real-time.

**Outcome:** Demonstrated the effectiveness of LSTM networks in handling temporal data for fraud detection, paving the way for enhanced transaction monitoring and fraud prevention systems.

**Key Contributions:**

Developed a deep learning model using LSTM tailored for credit card fraud detection.
Applied SMOTE to address class imbalance and improve model performance on imbalanced datasets.
Provided clear visualizations of model training metrics and evaluation results for easy interpretation.
**Future Directions:** Future work could explore ensemble techniques, feature engineering, and real-time implementation for scalable deployment in financial institutions.

This project underscores the application of deep learning and resampling techniques in safeguarding financial transactions against fraudulent activities, promoting security and trust in electronic payments.
