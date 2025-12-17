# Image Similarity using Logistic Regression

[![Python](https://img.shields.io/badge/python-3.x-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

This project demonstrates **image similarity detection** using a **logistic regression model**. It predicts whether two images are similar based on extracted features.

## Features

- Compare images using feature vectors.
- Logistic regression classifier for similarity prediction.
- Modular and easy-to-extend code.

## Dataset

Images are organized into folders by category. Pairs of images are created for training the similarity model.

## How It Works

1. **Preprocessing:** Resize and normalize images.  
2. **Feature Extraction:** Raw pixels or pre-trained embeddings.  
3. **Training:** Logistic regression trained on labeled image pairs.  
4. **Prediction:** Predict similarity for new image pairs.  

## Requirements

- Python 3.x  
- `numpy`, `pandas`, `scikit-learn`, `opencv-python` or `Pillow`, `matplotlib` (optional)

```bash
pip install numpy pandas scikit-learn opencv-python matplotlib
