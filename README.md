# Feature Selection & Dimensionality Reduction - Wisconsin Breast Cancer Classification

## Introduction
Feature selection and dimensionality reduction allow us to minimise the number of features in our dataset by only keeping features that are important. In other words, we want to retain features that contain the most useful information that is needed by our model to make accurate predictions while discarding redundant features that contain little to no information.

This repository contains a notebook which explores various feature selection and dimensionality reduction techniques in reference to the [Wisconsin breast cancer dataset](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) on Kaggle. This dataset contains 569 breast cancer observations in which 357 of them are benign and 212 of them are malignant. The goal is to train a machine learning model that is able to classify a random breast cancer observation as either benign or malignant. I have chosen the random forest classifier for this particular problem but feel free try out other classification models of your choice.

The techniques that will be covered in this notebook as follows:

- Variance inflation factor (VIF)
- Univariate feature selection
- Recursive feature elimination
- Model-based feature selection
- Principal component analysis (PCA)

We will compare the effectiveness of each technique by examining the accuracy of our model at making predictions. More specifically, we will be using the confusion matrix, which is a common approach to test the performance of a model in binary classification.

## Data description
The columns of the dataset represent 10 real-valued features of each cell nucleus:

1. Radius
2. Texture
3. Perimeter
4. Area
5. Smoothness 
6. Compactness
7. Concavity
8. Concave points
9. Symmetry
10. Fractal dimension

The mean, standard error and worst of each feature were also computed, resulting in a total of 10 x 3 = 30 features (columns) in the dataset excluding the target variable.

## Conclusion
- Variance inflation factor (98.83% accuracy with 25 features)
- Univariate feature selection (95.32% accuracy with 5 features)
- Recursive feature elimination (95.91% accuracy with 5 features)
- Model-based feature selection (97.08% accuracy with 9 features)
- Principal component analysis (97.08% with 4 principal components)

Despite using a significantly less number of features, we still managed to come very close the accuracy score under the base case scenario (98.25% accuracy) where all the features in the dataset were used to train our model. 

## Medium article
Link to full write-up on Towards Data Science [here](https://towardsdatascience.com/feature-selection-dimensionality-reduction-techniques-to-improve-model-accuracy-d9cb3e008624).

## Additional resources
- [Random forest](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ)
- [Confusion matrix](https://www.youtube.com/watch?v=8Oog7TXHvFY&t=1681s)
- [Principal component analysis](https://www.youtube.com/watch?v=FgakZw6K1QQ)
- [Scikit-learn feature selection documentation](https://scikit-learn.org/stable/modules/feature_selection.html)

## Follow me 
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/jasonchong914)
- [Medium](https://www.medium.com/@chongjason)
