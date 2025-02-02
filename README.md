# Image Classification Project

- **Purpose:**  
  Image classification using three approaches:
  - **KNN:** Optimal K via k-fold cross-validation.
  - **SVM:** PCA-based dimensionality reduction and linear SVM.
  - **CNN:** End-to-end convolutional neural network.

- **Dataset:**  
  Images organized by class stored in Google Drive (update `data_path` in the code accordingly).

- **Dependencies:**  
  - numpy  
  - tensorflow  
  - scikit-learn  
  - matplotlib  
  - seaborn

- **Usage:**  
  1. Upload the code to Google Colab.
  2. Mount Google Drive and update the dataset path.
  3. Run the notebook cells sequentially.

- **Results:**  
  - Model evaluations include accuracy, confusion matrices, precision, and recall.
  - A bar plot compares the performance of KNN, SVM, and CNN models.
