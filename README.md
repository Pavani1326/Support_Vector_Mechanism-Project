# Support_Vector_Mechanism-Project

# Project Title:
Using the support Vector machine algorithm of supervised machine learning, predict iris.csv dataset to find out species willl be same or different to find out

# Problem Statement:
A American based botonical garden grow iris flower in there labs but using bio technology in a single tree diffferent type of variety flower is grow.
As a data science enginer to find out how much accuracy is there all category contains same species.

TASK-1

Pre process the data skit.learn library

TASK-2

Load the data using sklearn model selection using default argument

TASK-3

On the bases of the dataset tain test and split SPM model

TASK-4

Impliment support vector machanisum classifier using SVM_ classifier.The SVM must be "Linear"

TASK-5

Train the classifier on the training data

TASK-6

Find out the prediction value on the test data

TASK-7

Test the model with the help of accuracy, accuracy should be lie



# Project Approch
## Train the classifier on the training data
svm_classifier.fit(X_train, y_train)

SVC
SVC(kernel='linear')

# Project Accuracy
## Calculate accuracy
accuracy = accuracy_score(y_test, y_pred)
print(f"Accuracy: {accuracy:.2f}")

Accuracy: 1.00

# Conclusion:

According to my support vector mechanisum model the species are linear with the accuracy of 1.00
Hence proves model was successfully implement
