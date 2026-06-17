# Face Recognition Using PCA and ANN

## Project Overview

This project implements a Face Recognition System using Principal Component Analysis (PCA) and an Artificial Neural Network (ANN). PCA is used to reduce the dimensionality of facial images by extracting important features known as Eigenfaces, while ANN is used to classify and recognize individuals based on these features.

## Objectives

* Perform face recognition using image processing techniques.
* Reduce dimensionality using PCA.
* Train an ANN classifier on extracted facial features.
* Evaluate recognition performance using classification accuracy.
* Analyze the impact of different PCA components (K values) on accuracy.

## Technologies Used

* Python
* NumPy
* OpenCV
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

## Dataset

The dataset consists of grayscale face images belonging to multiple individuals. Images are resized and converted into feature vectors before processing.

## Methodology

1. Load and preprocess face images.
2. Convert images into grayscale and resize them.
3. Normalize pixel values.
4. Split dataset into 60% training and 40% testing data.
5. Apply PCA to extract Eigenfaces.
6. Train an ANN classifier using PCA features.
7. Predict identities on the test set.
8. Evaluate classification accuracy.
9. Compare accuracy for different K values.

## Results

* PCA successfully reduced image dimensionality.
* ANN learned facial feature representations from Eigenfaces.
* Best Test Accuracy Achieved: 61%

## Project Structure

Face_Recognition_PCA_ANN/

├── face_recognition.ipynb

├── README.md

├── report.pdf

├── pca_ann_model.h5

└── screenshots/

```
├── dataset_loaded.png

├── train_test_split.png

├── model_summary.png

├── final_accuracy.png

└── accuracy_vs_k.png
```

## Conclusion

The face recognition system was successfully developed using PCA and ANN. PCA reduced computational complexity by extracting significant facial features, while ANN performed classification. The system achieved an accuracy of 61% on the testing dataset.
