# Random-Forest-Classifier

A Random Forest Classifier is a machine learning algorithm that belongs to the ensemble learning category. It is primarily used for classification tasks, although it can also be adapted for regression tasks (in which case it's called a Random Forest Regressor). Random Forests are known for their robustness and high predictive accuracy, making them a popular choice for various data-driven applications.

A Random Forest is essentially an ensemble of decision trees. It creates multiple decision trees during training, and each tree independently makes predictions.The ensemble nature of Random Forests helps reduce overfitting compared to single decision trees, as the individual trees may overfit the data differently.Random Forests tend to provide high predictive accuracy and are less sensitive to outliers and noisy data.

## Implementation

- Importing the required Libraries
- Reading the dataset
- Performing EDA on the dataset
- Checking for outliers
- Encoding the Categorical Variables 
- Normalization of the data
- Splitting the data into Train and Test data
- K-Fold Cross Validation
- Building Model using Random Forest Classifier
- Predictions and finding the Accuracy 
- Conclusion

## Packages Used

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- warnings
- from sklearn.model_selection import train_test_split
- from sklearn.model_selection import KFold
- from sklearn.model_selection import cross_val_score
- from sklearn.ensemble import RandomForestClassifier



