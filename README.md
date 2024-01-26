# Disease Prediction System

This project involves the development of a disease prediction system using machine learning techniques. The system utilizes a dataset containing symptoms and corresponding disease prognoses. The goal is to build robust models that accurately predict diseases based on input symptoms.

## Project Overview

### 1. Dataset
The dataset used in this project contains symptoms as features and the associated disease prognosis as the target variable. Two CSV files, one for training and one for testing, are employed. The dataset is preprocessed to handle null values, convert labels to numerical format, and ensure data cleanliness.

### 2. Data Exploration
Initial exploration involves checking the balance of the dataset, visualizing disease distribution, and ensuring a comprehensive understanding of the dataset.

### 3. Model Building
Three machine learning models are employed for disease prediction:
- **Support Vector Classifier (SVC):** A discriminative classifier seeking an optimal hyperplane.
- **Gaussian Naive Bayes Classifier:** A probabilistic algorithm using Bayes' Theorem for classification.
- **Random Forest Classifier:** An ensemble learning algorithm utilizing multiple decision trees.

### 4. Model Evaluation and K-Fold Cross-Validation
Models are evaluated using K-Fold cross-validation to ensure reliable performance assessment. Mean scores provide insights into the overall efficacy of each model.

### 5. Model Combination
To enhance robustness, the predictions of all three models are combined. This involves taking the mode of predictions, aiming for increased accuracy even if individual models make incorrect predictions.

### 6. Final Testing
The combined model is tested on new and unseen data from the test dataset. Evaluation metrics such as accuracy and confusion matrices are employed to assess the model's performance.

## Usage

1. **Environment Setup:**
   - Install necessary libraries using `pip install -r requirements.txt`.
   - Ensure Jupyter Notebook environment for code execution.

2. **Dataset Preparation:**
   - Place the training dataset (`Training.csv`) and testing dataset (`Testing.csv`) in the `dataset` folder.

3. **Code Execution:**
   - Execute the Jupyter Notebook cells sequentially for data preprocessing, model building, and evaluation.

4. **Results:**
   - Analyze the visualizations and evaluation metrics to gauge the performance of individual models and the combined model.

## Conclusion

This disease prediction system provides a valuable tool for healthcare applications, offering accurate predictions based on symptoms. The combination of multiple models ensures robustness and reliability in disease prognosis. Continuous improvement and exploration of additional features can further enhance the system's predictive capabilities.

Feel free to customize and extend the project based on specific requirements and additional datasets.
