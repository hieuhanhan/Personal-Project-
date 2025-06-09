# Recyclable Waste Classification

This project demonstrates a machine learning approach to classify wastes as recyclable or non-recyclable using image data. The goal is to assist in automated waste sorting, improving recycling efficiency and reducing environmental impact.

## Project Overview:

- **Notebook:** `recyclable-waste-classification.ipynb`
- **Category:** Computer Vision, Classification, Machine Learning

## Dataset

The project uses a dataset of waste images categorized into recyclable and non-recyclable classes. Each image is labeled accordingly. Details about the dataset source and structure are provided in the notebook.

## Approach

1. **Data Preprocessing:**  
   Images are loaded, resized, and normalized for model training.

2. **Model Building:**  
   A convolutional neural network (CNN) is implemented to classify the images.

3. **Training & Evaluation:**  
   The model is trained on the labeled dataset and evaluated using accuracy and confusion matrix metrics.

4. **Results & Discussion:**  
   The notebook presents model performance, discusses misclassifications, and suggests improvements.

## How to Run

1. Open `recyclable-waste-classification.ipynb` in Jupyter Notebook or VS Code.
2. Follow the cells sequentially to preprocess data, train the model, and view results.
3. Ensure required libraries (e.g., TensorFlow, Keras, NumPy, Matplotlib) are installed.

## Requirements

- Python 3.x
- TensorFlow/PyTorch
- NumPy
- Matplotlib
- scikit-learn

Install dependencies with:
```sh
pip install -r requirements.txt
```






