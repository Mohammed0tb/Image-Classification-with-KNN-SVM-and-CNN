# Image Classification Project

This project demonstrates how to classify images using three different approaches:

- **Data Loading & Preprocessing:**
  - Loads images from a specified source on Google Drive.
  - Resizes, normalizes, and balances the dataset by sampling a fixed number of images per class.

- **Modeling Approaches:**
  - **K-Nearest Neighbors (KNN):**  
    Uses k-fold cross-validation to determine the optimal number of neighbors and evaluates classification performance.
  - **Support Vector Machine (SVM) with PCA:**  
    Applies Principal Component Analysis for dimensionality reduction before training a linear SVM, and evaluates the model with accuracy, precision, and recall.
  - **Convolutional Neural Network (CNN):**  
    Implements an end-to-end CNN to classify images, providing an alternative deep learning approach.

- **Evaluation & Visualization:**
  - Generates confusion matrices and classification reports for each model.
  - Compares model performances using bar plots to visualize accuracy, precision, and recall.

- **Dataset Source:**  
  The project uses an image dataset organized by class.  
  **Source Data:** [Link to Dataset]([https://your-dataset-link.com](https://www.kaggle.com/datasets/sachinkumar413/covid-pneumonia-normal-chest-xray-images?select=PNEUMONIA))

## Usage

1. Open the notebook in Google Colab.
2. Mount your Google Drive and update the `data_path` variable to point to your dataset.
3. Run the notebook cells sequentially to load data, train models, evaluate performance, and visualize results.
