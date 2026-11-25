# Fashion-MNIST Classification using CNN

A Deep Learning project built using **TensorFlow and Keras** to classify Fashion-MNIST images into 10 clothing categories using a Convolutional Neural Network (CNN).

## Technologies
- Python
- TensorFlow & Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset
- Dataset: Fashion-MNIST
- Training Images: 60,000
- Testing Images: 10,000
- Image Size: 28 × 28 (Grayscale)
- Classes: 10

## CNN Architecture
- Conv2D (32, 64, 128 filters)
- ReLU Activation
- MaxPooling2D
- Dropout (0.5)
- Flatten
- Dense Layers
- Softmax Output

## Workflow
1. Loaded and explored Fashion-MNIST dataset.
2. Preprocessed and normalized images.
3. Built CNN architecture.
4. Trained the model for 15 epochs.
5. Monitored training and validation performance.
6. Applied Dropout to reduce overfitting.
7. Evaluated predictions on test data.
8. Generated confusion matrix and classification report.

## Results

| Metric | Accuracy |
|---|---:|
| Training Accuracy | 93.69% |
| Validation Accuracy | 91.81% |
| Test Accuracy | **91%** |

**Test Loss:** 0.2743

## Evaluation
- Accuracy & Loss
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

## Key Learnings
- CNN architecture and feature extraction.
- Overfitting and regularization.
- Dropout and data augmentation.
- Multiclass image classification.
- Model evaluation and performance analysis.


