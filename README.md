# Predictive-Modeling-Using-Machine-learning
A beginner-friendly Machine Learning project that predicts student pass/fail outcomes based on study hours using a Decision Tree Classifier. The project includes data preprocessing, model training, accuracy evaluation, confusion matrix visualization, and prediction of new outcomes.
# Predictive Modeling Using Machine Learning

## Project Overview

This project demonstrates a simple Machine Learning predictive model that predicts whether a student will pass or fail based on the number of hours studied.

The project uses a Decision Tree Classifier and includes:

- Data loading and preprocessing
- Model training
- Model testing
- Accuracy evaluation
- Confusion Matrix visualization
- Prediction on new data

---

## Objective

To build a predictive model using supervised machine learning techniques and evaluate its performance using standard metrics.

---

## Dataset

The dataset contains two columns:

| Hours_Studied | Pass |
|--------------|------|
| 1 | 0 |
| 2 | 0 |
| 3 | 0 |
| 4 | 0 |
| 5 | 1 |
| 6 | 1 |
| 7 | 1 |
| 8 | 1 |
| 9 | 1 |
| 10 | 1 |

Where:

- 0 = Fail
- 1 = Pass

---

## Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib

---

## Machine Learning Algorithm

The project uses:

### Decision Tree Classifier

A Decision Tree is a supervised learning algorithm used for classification tasks. It learns patterns from training data and predicts outcomes for new data.

---

## Project Workflow

1. Create and upload dataset
2. Load dataset using Pandas
3. Split data into training and testing sets
4. Train Decision Tree model
5. Test model performance
6. Calculate accuracy
7. Generate Confusion Matrix
8. Predict student result based on study hours

---

## Results

The model successfully predicts whether a student will pass or fail based on study hours.

Evaluation metrics used:

- Accuracy Score
- Confusion Matrix

---

## Sample Prediction

Input:

```python
hours = [[7]]
```

Output:

```text
Student Will Pass
```

---

## Future Improvements

- Use larger datasets
- Apply Random Forest and Logistic Regression
- Add ROC Curve visualization
- Create a web application using Flask or Streamlit

---

## Learning Outcomes

Through this project, I learned:

- Supervised Machine Learning
- Data preprocessing
- Model training and testing
- Model evaluation techniques
- Performance visualization using Confusion Matrix

---

## Author

Supriya Gudapati

Machine Learning Beginner Project
