# Toxicity-Detection-NLP
Comparison of Logistic Regression and Linear SVM for toxic comment detection using TF-IDF features.

## Objective

Build a machine learning model to classify comments as Toxic or Non-Toxic.

## Dataset

Jigsaw Toxic Comment Classification Dataset

## Models Evaluated

1. Logistic Regression
2. Linear SVM

## Pipeline

Comment Text
→ TF-IDF Vectorization
→ Classification Model
→ Toxic / Non-Toxic

## Results

### Logistic Regression

* Accuracy: 95.77%
* Precision: 0.91
* Recall: 0.62
* F1 Score: 0.74

### Linear SVM

* Accuracy: 95.99%
* Precision: 0.88
* Recall: 0.68
* F1 Score: 0.76

## Key Findings

* Linear SVM achieved better recall and F1-score.
* Accuracy alone was misleading because the dataset was imbalanced.
* Recall proved to be a more important metric for toxicity detection.

## Future Improvements

* Class-weight balancing
* BERT-based classification
* Sentence embeddings (MiniLM)
* RAG-based text detoxification

