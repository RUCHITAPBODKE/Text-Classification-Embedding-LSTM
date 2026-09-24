# Text Classification using Embedding and Bidirectional LSTM

## Practical No. 02

A multiclass text classification model using an Embedding layer
and Bidirectional LSTM network on the Reuters Newswire dataset.

## Objective

To build and evaluate a multiclass text classification model using
an Embedding layer and LSTM network.

## Dataset

The Reuters Newswire dataset from Keras is used.

- Training samples: 8,982
- Testing samples: 2,246
- Number of classes: 46
- Task: Multiclass text classification

## Model Architecture

Input Text
↓
Tokenization
↓
Padding
↓
Embedding Layer
↓
Bidirectional LSTM
↓
Dropout
↓
Dense Layer
↓
Softmax Output
↓
46 Classes

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results

| Metric | Score |
|---|---:|
| Accuracy | 72.26% |
| Precision | 67.89% |
| Recall | 72.26% |
| F1 Score | 69.72% |

## Visualizations

The project includes:

- Class distribution
- Article length distribution
- Training vs validation accuracy
- Training vs validation loss
- Confusion matrix

## How to Run

### Install dependencies

```bash
pip install -r requirements.txt
