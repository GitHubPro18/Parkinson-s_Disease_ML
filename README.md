# Parkinson's_Disease_Voting_Classifier
## **Project Overview**<br>
This project focuses on classifying images into two categories: spiral and wave. The project uses several machine learning models for this task, including Random Forest, Support Vector Machine (SVM), Naive Bayes, and K-Nearest Neighbors (KNN). It employs Histogram of Oriented Gradients (HOG) for feature extraction from the images. Additionally, an ensemble Voting Classifier is used to improve classification accuracy by combining the strengths of individual models.

## **Project Structure**<br>
- Image Loading & Display: Visualizes the training and testing images.<br>
- Feature Extraction: HOG features are extracted from images resized to 128x128 pixels.<br>
- Model Training:<br>
    - Random Forest<br>
    - Support Vector Machine (SVM)<br>
    - Naive Bayes<br>
    - K-Nearest Neighbors (KNN)<br>
- Hyperparameter Tuning: Performed for SVM and Naive Bayes classifiers.<br>
- Model Evaluation: Accuracy metrics are used to evaluate the performance of each model.<br>
- Voting Classifier: An ensemble model that combines all classifiers for improved performance.<br>
- Dataset<br>
    The dataset includes images categorized into two classes:<br>
      - spiral<br>
      - wave<br>
    Each class has separate directories for training and testing data.<br>

## **Key Results**<br>
- Best Alpha for Naive Bayes: 0.1<br>
- Spiral Naive Bayes Accuracy: 76.67%<br>
- Wave Naive Bayes Accuracy: 70%<br>
- Spiral Random Forest Accuracy: 76.67%<br>
- Wave Random Forest Accuracy: 70%<br>
- KNN Accuracy: 83.33%<br>
- SVM Accuracy: 73.33%<br>
- Voting Classifier Accuracy: 80%<br>
