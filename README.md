# Machine Learning Assignment

This project explores several machine learning models and deep learning techniques across three tasks.

## Q1 — Classical ML Models
- Loaded and preprocessed **Dataset2** (missing values, one-hot encoding, normalization).
- Split data into train/validation/test sets.
- Trained:
  - Random Forest (5 trees, max depth 5)
  - Single-Layer Perceptron (SGD)
  - Multi-Layer Perceptron (2 hidden layers: 50 & 100 units)
- Recorded training times and plotted Random Forest feature importances.
- Selected features covering 90% cumulative importance.

## Q2 — Model Evaluation
- Evaluated each model on the test set using:
  - Confusion matrix  
  - Accuracy, Precision, Recall, F1-score  
  - Test-time (ms)
- Plotted **multiclass ROC curves** (micro-average).
- Plotted **MLP learning curves** and discussed overfitting.

## Q3 — CNN on MNIST
- Loaded and normalized MNIST handwritten digit images.
- Designed a CNN with 3 convolutional layers, max pooling, and dense layers.
- Trained for 10 epochs with a validation split.
- Plotted accuracy and loss curves.
- Evaluated accuracy and macro F1-score on the MNIST test set.
- Discussed whether the model shows overfitting.

---
