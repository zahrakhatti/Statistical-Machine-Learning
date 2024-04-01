# Statistical-Machine-Learning

This repository has been created for this specific course. 
It contains the code for the class project. 
My project is on fairness learning.
The dataset is the Adult dataset which predicts one if the income is greater than 50k dollars and zero otherwise.

The 'sensitive' code is showing that we have different accuracies for men and women even if we ignore using gender as the sensitive feature.
The 'reg-cov' code is showing that by adding a covariance term to the objective function as a regularization term, we can mitigate the difference between accuracies of male and female.
The 'const-cov' is my current work which is going to show that adding a hard constraint to the objective function is better than regualization term.
