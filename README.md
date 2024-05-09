# Machine Learning Projects

 A combination of 2 projects that test for classification and regression respectively. 
 Worked on data involving ‘brain strokes' and 'airplane crashes'. 

## Brain Stroke Classification

Developed various models, such as KNN and SVM to predict the number of occurrences of brain strokes. 

#### Basic EDA
![box_plot](https://github.com/jenu-21/machine-learning-project/assets/133542213/60df8f01-e73c-4dc4-aad1-19a44c02dda7)

#### Process of machine learning classification

##### Normalise the data
- To ensure the categorical variables are encoded for the tests

##### Train-Test Split 
- The train-test split is a crucial step in machine learning model development, primarily for evaluating the model's performance and generalisation ability
![encode](https://github.com/jenu-21/machine-learning-project/assets/133542213/293b1f9a-6f53-487b-964d-f9055fdc0153)

- Scaling the data ensures that the machine learning algorithm can effectively learn from the data and produce better results, especially for algorithms sensitive to feature scales.
  ![scaling](https://github.com/jenu-21/machine-learning-project/assets/133542213/c779ae96-efb0-4deb-8a83-d1fd973d6bf1)

##### Using Predictions
![predictions](https://github.com/jenu-21/machine-learning-project/assets/133542213/20f2a43c-f2e1-458e-b967-6cc58cd704a0)

##### Classification Report with confusion matrix 
![classification report](https://github.com/jenu-21/machine-learning-project/assets/133542213/ed880e5e-7ad1-48ab-83d0-4082d14d7258)

All these processes have been applied to various classification methods such as KNN, Dtree, SVM AND Gradient boosting machine

##### Issue of imbalanced dataset
![distribution_of_stroke](https://github.com/jenu-21/machine-learning-project/assets/133542213/f1893433-b210-4198-b90a-3c4af6dad963)

This was sorted by utilising techniques such as random oversampling, SMOTE and other sampling techniques to get results like this
![confusion_matrix_resampled](https://github.com/jenu-21/machine-learning-project/assets/133542213/8659a24f-08cd-4d8a-b9ff-145fcabcdba4)


## Airplane Crash Regression Analysis

Performed various regression analysis such as multiple linear and polynomial regressions to predict the number of occurrences of crashes.

#### Data Cleaning

- Removed null values, particularly in key columns of consideration
  
![remove_nulls](https://github.com/jenu-21/machine-learning-project/assets/133542213/86293e37-6977-4454-87de-a7281c9de31f)

#### EDA 
![airplane_crash_correlation](https://github.com/jenu-21/machine-learning-project/assets/133542213/28cb0b5a-0ffa-4839-a3b5-68d0a3863c53)

#### Regression Analysis 

- Similar methods of the prior project above with train-testing split, encoding categorical variables, predictions

##### Methods incorporated
The regression analysis was done on 3 models:
- Multiple Linear
- Polynomial
- Ridge Regression

Utilising MSE, RMSE and R-Squared test to evaluate the best model 
![evaluation_regression_models](https://github.com/jenu-21/machine-learning-project/assets/133542213/2177ed4a-3d95-4369-a49c-e0609593a772)



