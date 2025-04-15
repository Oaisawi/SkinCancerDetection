# Skin Cancer Detection using Machine Learning

This project explores the use of machine learning models to classify skin cancer from a large-scale image dataset. The models are trained and evaluated using structured metadata and image data from over 400,000 samples.

## Approaches Used
- Logistic Regression (metadata-based)
- Convolutional Neural Networks (image-based)

## Features
- Data preprocessing and cleaning
- Label encoding for categorical features
- Class imbalance handling (undersampling)
- CNN-based classification using image data
- Evaluation with classification reports and confusion matrices

## Files
- `ML project logistic regression.ipynb` – uses metadata with logistic regression
- `ML project CNN.ipynb` – builds and trains a CNN using skin lesion images

## Requirements
- Python 3.x
- scikit-learn
- pandas, numpy
- TensorFlow / Keras
- OpenCV

Install dependencies with:
```bash
pip install scikit-learn pandas numpy tensorflow opencv-python
