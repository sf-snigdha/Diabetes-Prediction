# Diabetes-Prediction
In this project I will be using Machine Learning techniques to predict whether any person is suffering from Diabetes

In this machine learning project, I have collected the dataset from Kaggle  and I will be using Machine Learning to predict whether any person is suffering from Diabetes.


# Algorithms

Here I experimented with 3 algorithms-
KNeighborsClassifier
DecisionTreeClassifier
RandomForestClassifier
to find the accuracy of the prediction



# feature selection

I did the feature selection using seaborn and got the correlations of each features in dataset.
Then i analyzed the histogram pf each column properties to have a betterr understanding of the features.
I observed the comparison of sizes of the outcome classes of the dataset.



# Data Processing

After exploring the dataset, I observed that I need to convert some categorical variables into dummy variables and scale all the values before training the Machine Learning models. First, I used the get_dummies method to create dummy columns for categorical variables.



Then I used all 3 algorithms to find the accuracies and observed that the accuracies were quite similarly good. But the accuracy result of Random Forest Classifier was the best.
