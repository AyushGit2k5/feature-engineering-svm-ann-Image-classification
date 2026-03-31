# Handwritten-symbol-classification-svm-ann
## Problem
Built an image classification system to recognize handwritten mathematical symbols, with the goal of systematically investigating how different feature extraction techniques and classifiers influence classification accuracy.

## Dataset
Custom-generated dataset of handwritten mathematical symbols, consisting of multiple classes with grayscale image samples. Each class contains variations in writing style, introducing intra-class variability and inter-class similarity.

## Approach
Implemented and compared two classifiers:
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)

Extracted and evaluated three feature representations:
- Histogram of Oriented Gradients (HOG)
- Local Binary Patterns (LBP)
- Raw pixel values

Conducted a controlled comparison by training each classifier on all feature types to analyze which feature–model combinations yield the best performance.

## Evaluation
Evaluated models using classification accuracy across all feature–classifier combinations. Generated confusion matrices for the best-performing configuration to analyze misclassification patterns and class-level performance.

## Results
Performance varied significantly depending on the feature representation. HOG-based features generally provided the strongest results due to their ability to capture shape and edge information, while raw pixel inputs were less effective. The comparative analysis highlights the importance of feature extraction in traditional machine learning pipelines.

## Future Improvements
Potential improvements include hyperparameter tuning for both SVM and ANN, exploring additional feature extraction methods, applying dimensionality reduction techniques, and extending the approach using convolutional neural networks for end-to-end feature learning.
