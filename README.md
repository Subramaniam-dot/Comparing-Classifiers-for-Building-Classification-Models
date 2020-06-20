# Comparing-Classifiers-for-Building-Classification-Models
#### we will be comparing the performance of ***different classifiers*** for building classification models for Breast Cancer Wisconsin Dataset.

# Algorithm:
1. Make breast cancer dataset
2. Data split (80/20 ratio)
3. Build Classification Models
4. Build Model, Apply Model on Test Data & Record Accuracy Scores
5. Analysis of Model Performance

## Make breast cancer dataset:
Make the dataset by importing from sklearn and make classification of features and class label from sklearn.datasets

## Data split (80/20 ratio):
Split the dataset into Training set and Test set, where 80% of the dataset is assigned to Training set and 20% is assigned to Test set.

## Build Classification Models:

# Classifiers used:
- Nearest Neighbors
- Linear SVM
- Polynomial SVM
- RBF_SVM
- Gaussian Process Classifier
- GradientBoosting Classifier
- Decision Tree Classifier
- ExtraTrees Classifier
- RandomForest Classifier
- Multi-layer Perceptron C lassifier
- AdaBoost Classifier
- Gaussian Naive Bayes Classifier
- Quadratic Discriminant Analysis
- SGDClassifier

# Build Model, Apply Model on Test Data & Record Accuracy Scores:

| Name        | Score       |
| ----------- | ----------- |
| Nearest_Neighbors      | 0.912281       |
| Linear_SVM | 0.938596        |
| Polynomial_SVM | 0.877193        |
| RBF_SVM | 0.640351        |
| Gaussian_Process | 0.903509        |
| Gradient_Boosting | 0.964912        |
| Decision_Tree | 0.929825        |
| Extra_Trees | 0.964912        |
| Random_Forest | 0.964912        |
| Neural_Net | 0.912281        |
| AdaBoost | 0.991228        |
| Naive_Bayes | 0.938596        |
| QDA | 0.956140        |
| SGD | 0.921053        |

# Color wise Table for model performance
**Dark Green color to Light**, where Dark shade has high score for that respective classifier and Light shade has less score for that respective classifier.

![](https://github.com/Subramaniam-dot/Comparing-Classifiers-for-Building-Classification-Models/blob/master/imag1.JPG?raw=true)


# Bar plot of model performance
Here is the  Bar Plot of model performance, where X axis is the Score for the Classifiers and Y axis is name of the classifiers. 

![](https://github.com/Subramaniam-dot/Comparing-Classifiers-for-Building-Classification-Models/blob/master/imag2.png?raw=true)


#### [Here is the link to the code](https://github.com/Subramaniam-dot/Comparing-Classifiers-for-Building-Classification-Models/blob/master/comparing_classifiers.ipynb)
