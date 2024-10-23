# Heart Attack Risk Prediction

This project involves a classification task to predict the risk of heart attacks using a [dataset](https://www.kaggle.com/datasets/m1relly/heart-attack-prediction). from kaggle. The project includes data preprocessing, feature engineering, and model training using various machine learning algorithms.

## Dataset

The dataset contains information about patients, including:

- Age
- Sex
- Cholesterol
- Blood Pressure
- Heart Rate
- Diabetes
- Family History
- Lifestyle factors (Smoking, Obesity, etc.)
- Heart Attack Risk (target variable)

## Project Structure

- **heart_attack_risk.csv**: The dataset used for training and testing models.
- **heart_attack_risk_prediction.ipynb**: Jupyter notebook that processes the data and trains several classification models.

## Key Steps

1. **Data Preprocessing**: 
   - Handling missing values and duplicates.
   - Splitting blood pressure into systolic and diastolic.
   - Encoding categorical variables using One-Hot Encoding and Label Encoding.

2. **Feature Engineering**:
   - Transforming features for better model performance.
   - Dimensionality reduction using PCA.

3. **Model Training**:
   - Training multiple models including Logistic Regression, Decision Tree, Random Forest, SVM, and others.
   - Evaluating models based on accuracy and specificity.

4. **Neural Network Model**:
   - Implementing a neural network using TensorFlow for prediction.

5. **Feature Selection**:
   - Using techniques like Lasso and Random Forest to select important features.

## How to Run

1. Clone the repository.
2. Place `heart_attack_risk.csv` in the same directory as the notebook.
3. Run `heart_attack_risk_prediction.ipynb` to execute the analysis and view results.

## Results

The project evaluates various models to determine which is most effective for predicting heart attack risk, with visualizations of accuracy and other metrics.
