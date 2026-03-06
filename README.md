# Probabilistic_models_Decision_Trees_Machine_Learning
​The assignment focuses on probabilistic models and decision trees for classification tasks. ​ The main objectives include implementing and evaluating Gaussian generative classifiers, Gaussian Naive Bayes, decision trees, and random forests. ​

This project is divided into four main parts:
## Part A: Gaussian Generative Classifier ​
1. Dataset: Handwritten Digits (scikit-learn's load_digits).​
2. Objective: Implement a Gaussian generative classifier with shared covariance matrix for handwritten digit recognition.   ​
3. Tasks:
- Estimate class priors, class means, and shared covariance matrix. ​
- Regularize the covariance matrix and tune the regularization parameter (λ). ​
- Evaluate the model using test accuracy, macro-averaged precision, recall, F1-score, and confusion matrix. ​

## Part B: Gaussian Naive Bayes ​
1. Dataset: Adult Income Dataset (Census Income).   ​
2. Objective: Implement a Gaussian Naive Bayes classifier for income classification using categorical features.   ​
3. Tasks:
- Encode categorical features and handle missing values. ​
- Implement Naive Bayes with Laplace smoothing (α).
- Compare performance with scikit-learn's MultinomialNB. ​

## Part C: Decision Tree ​
1. Dataset: Breast Cancer Wisconsin (Diagnostic) (scikit-learn's load_breast_cancer).   ​
2. Objective: Implement a binary decision tree classifier for continuous features to classify malignant vs. benign tumors.   ​
3. Tasks:
- Use entropy and information gain for split selection. ​
- Implement stopping criteria (max_depth, min_samples_split). ​
- Tune hyperparameters and evaluate performance using accuracy, precision, recall, F1-score, and confusion matrix. ​

## Part D: Random Forest (Bonus) ​
1. Dataset: Breast Cancer Wisconsin (Diagnostic).   ​
2. Objective: Implement a random forest classifier using the decision tree implementation from Part C.   ​
3. Tasks:
- Train multiple decision trees on bootstrap samples. ​
- Use majority voting for final predictions. ​
- Tune hyperparameters (number of trees, max_features) and compare performance with a single decision tree.


## Prerequisites
To run this project, you need the following:
1. Python 3.8+
2. Libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- seaborn

### IDE/Editor: Jupyter Notebook or any Python IDE



