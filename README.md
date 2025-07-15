# Logistic Regression

In this project, I implement logistic regression and apply it to two different datasets:

 - Binary classification with linearly separable data
 - Regularized logistic regression with non-linearly separable data

## Logistic Regression (Linearly Separable Data)

Suppose you are the administrator of a university department and want to determine each applicant’s chance of admission based on their results on two exams.

 - You have historical data from previous applicants to use as a training set for logistic regression.
 - For each training example, you have the applicant’s scores on two exams and the admission decision.
 - Your task is to build a classification model that estimates an applicant’s probability of admission based on these scores.

### Results

After training the model, we visualize the data with a scatter plot. The line represents the learned decision boundary that separates admitted and not-admitted applicants:

<img width="603" height="434" alt="Screenshot 2025-07-15 at 14 56 38" src="https://github.com/user-attachments/assets/013edb32-3954-4b22-823a-cb138c22723d" />


## Regularized Logistic Regression (Non-Linear Decision Boundary)

Suppose you are the product manager at a microchip fabrication plant. Your goal is to predict whether microchips pass quality assurance (QA) based on results from two different tests.

 - You have historical test data for microchips, including whether they were accepted or rejected.

The data is not linearly separable, meaning a straight line cannot separate accepted from rejected microchips.

### Results

Using regularized logistic regression, the model learns a non-linear decision boundary that better separates accepted and rejected microchips.

<img width="615" height="436" alt="Screenshot 2025-07-15 at 15 07 43" src="https://github.com/user-attachments/assets/6c685d67-4985-4dbb-b554-9e8810649b5e" />


