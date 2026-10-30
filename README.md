# Audiobook Customer Engagement Prediction

## Project Overview

This project uses machine learning and a neural network to predict whether an audiobook customer is likely to make another purchase.

The goal is to identify patterns in customer behavior and use historical data to classify customers based on their likelihood of returning.

## Objectives

- Explore and prepare customer data for machine learning.
- Analyze customer purchasing and engagement behavior.
- Handle class imbalance in the target variable.
- Build and train a neural network using TensorFlow and Keras.
- Evaluate model performance on unseen data.

## Technologies Used

- **Python** — Data processing and model development
- **NumPy** — Numerical operations and array manipulation
- **Pandas** — Data analysis and preprocessing
- **Matplotlib** — Data visualization
- **Scikit-learn** — Data preparation and evaluation
- **TensorFlow / Keras** — Neural network development

## Project Workflow

1. **Data preprocessing**  
   Prepared the dataset and separated input features from the target variable.

2. **Data splitting**  
   Shuffled the observation indices and divided the dataset into training, validation, and test sets.

3. **Handling class imbalance**  
   Used random undersampling to reduce the majority class (0) in the training data and balance the target classes.

4. **Model development**  
   Built a neural network using TensorFlow and Keras.

5. **Model training**  
   Trained the model using validation data and early stopping to monitor generalization performance.

6. **Model evaluation**  
   Evaluated the trained model using a separate test dataset.

## Model Performance

| Metric | Result |
|---|---:|
| Test Accuracy | 82% |

*Accuracy is an initial result. Further evaluation using precision, recall, F1-score, and a confusion matrix is planned.*

## Key Learnings

Through this project, I gained practical experience with:

- Preparing real-world datasets for machine learning.
- Understanding and addressing class imbalance.
- Splitting datasets into training, validation, and test sets.
- Building neural networks with TensorFlow and Keras.
- Using early stopping during model training.
- Evaluating classification models on unseen data.

## Future Improvements

- Analyze the confusion matrix and classification report.
- Investigate precision, recall, and F1-score.
- Experiment with model architecture and hyperparameters.
- Compare different approaches to handling class imbalance.
- Improve model performance and generalization.

## Author

**Aayush Pokhrel**

GitHub: [@Ramseybolton](https://github.com/Ramseybolton)
