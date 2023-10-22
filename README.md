# random-foRest-diabetes

In this project, my goal was to predict the occurrence of diabetes within the Pima Indian population, known for its high prevalence of diabetes.

## Objectives

I divided this project into four main objectives:

1. **Data Preprocessing**: Generate a random training and test set from the data
2. **Exploratory Data Analysis**: Perform exploratory data analysis using the `ggplot2` package
3. **Machine Learning Models**: Apply the Random Forest Model machine learning model to the dataset
4. See how well my model performs by anaylzing the results using RMSE and a Confusion Matrix

## What I learned
- Creating an R markdown document to analyze a dataset, perform EDA, model building and evaluation
- Splitting data into training and test sets using ```caret's``` createDataPartition function
- Building a random forest classification model using the ```caret``` package with the ```ranger``` package being used to train the model.
- Evaluating model performance using confusionMatrix from ```caret```
- Comparing accuracy, sensitivity, specificity on the test set

## Conclusion

The test data set showed the model accuracy at 75.22%, correctly predicting diabetes status in 75.22% of individuals. Sensitivity was 82.24%, correctly identifying those with diabetes. Specificity was 61.54%, correctly identifying those without diabetes.

Type I error (false positive) occurred in 27 cases of incorrectly predicting diabetes where there was none. Type II error (false negative) occurred in 30 cases of incorrectly predicting no diabetes where there was.

## Future Improvement Strategies
Potential strategies to improve the model include:
- Feature Engineering: Investigate creating new predictive features by combining, transforming, or interacting existing features.
- Hyperparameter Tuning: Experiment with machine learning algorithm hyperparameters. For random forest, explore the number of trees and maximum tree depth.

