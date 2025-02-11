# Breast-Cancer-Classification-Using-Random-Forest

Overview:

This project implements a Random Forest Classifier to classify breast cancer tumors as either malignant or benign using the Breast Cancer Wisconsin Dataset from scikit-learn. The model is trained, optimized, and evaluated to achieve high accuracy in classification.

Dataset:

The dataset consists of 30 numerical features that describe tumor characteristics. It has two target classes:

Malignant (0): Cancerous tumors

Benign (1): Non-cancerous tumors

The dataset is divided into 80% training data and 20% testing data to ensure proper evaluation of the model.


Workflow:

Data Loading and Preparation: The dataset is loaded using scikit-learn, converted into a DataFrame for better handling, and split into training and testing sets.

Model Training: A Random Forest Classifier is trained on the dataset using default parameters and evaluated using 5-fold cross-validation.

Hyperparameter Tuning: The model undergoes hyperparameter optimization using GridSearchCV to improve accuracy and generalization.

Evaluation: The model is tested on unseen data, and key performance metrics such as accuracy, precision, recall, and F1-score are analyzed.

Visualization: A confusion matrix is plotted to better understand the model’s performance.

Results:

Cross-validation accuracy: ~95.82%

Test accuracy: ~96.49%

Precision, Recall, and F1-score:

Malignant: Precision=98%, Recall=93%, F1-score=95%

Benign: Precision=96%, Recall=99%, F1-score=97%

Conclusion:

This project demonstrates the effectiveness of Random Forest Classification for breast cancer detection. With an accuracy of 96.49%, the model provides a reliable method for identifying malignant and benign tumors. Future improvements can include advanced feature selection techniques and deep learning models for enhanced classification accuracy.



