# Logistic Regression

In this project, I implement logistic regression and apply it to two different datasets:

 - Binary classification with linearly separable data

 - Regularized logistic regression with non-linearly separable data

## Logistic Regression (Linearly Separable Data)

Suppose that you are the administrator of a university department and you want to determine each applicant’s chance of admission based on their results on two exams.

 - You have historical data from previous applicants that you can use as a training set for logistic regression.
 - For each training example, you have the applicant’s scores on two exams and the admissions decision.
 - Your task is to build a classification model that estimates an applicant’s probability of admission based on the scores from those two exams.

### Results

After training the model, we visualize the data with a scatter plot and the line represents the learned decision boundary that separates the admitted and not-admitted applicants:

<img width="603" height="434" alt="Screenshot 2025-07-15 at 14 56 38" src="https://github.com/user-attachments/assets/013edb32-3954-4b22-823a-cb138c22723d" />


### Model Evaluation

We use the model to predict outcomes on the training data and evaluate its accuracy.

Train Accuracy: 92%

The model performs well on linearly separable data, correctly classifying the majority of the training examples.


