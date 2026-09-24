# Practical No. 02 – Text Classification using Embedding Layer and LSTM

## Aim
To build a multiclass text classification model using an Embedding
layer and LSTM network and evaluate its performance using suitable
classification metrics.

## Dataset
Reuters Newswire Classification Dataset

- Total classes: 46
- Training samples: 8,982
- Testing samples: 2,246
- Task: Multiclass text classification

## Model Architecture

Embedding Layer
↓
Bidirectional LSTM
↓
Dropout
↓
Dense Layer
↓
Softmax Output (46 Classes)

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Visualizations

- Class Distribution
- Article Length Distribution
- Training vs Validation Accuracy
- Training vs Validation Loss
- Confusion Matrix
