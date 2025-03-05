# Crime-Rate-Prediction-Using-Machine-Learning

*Objectives:*
- Data Augmentation: Enhance the dataset through augmentation techniques to improve model performance and generalization.

- Model Evaluation: Assess the performance of various regression models using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

*Features:*

- Data Augmentation: To address the limited dataset size, data augmentation was performed by duplicating samples with added noise. This approach aimed to improve model robustness and generalization.

- Exploratory Data Analysis (EDA): Conducted EDA to understand feature distributions, relationships, and to identify patterns or anomalies in the data.

- Model Implementation: Developed and trained multiple regression models, including Linear Regression, Random Forest Regressor, Support Vector Regression (SVR), and a Sequential Deep Learning model.

- Model Evaluation: Evaluated models using MAE, MSE, and RMSE to determine prediction accuracy and model performance.

*Models:*
1. Linear Regression: A basic regression model that assumes a linear relationship between the independent variables and the target variable.

2. Random Forest Regressor: An ensemble learning method that constructs multiple decision trees to improve predictive accuracy and control over-fitting.

3. Support Vector Regression (SVR): A regression model that uses support vector machines to perform linear and non-linear regression.

4. Sequential Deep Learning Model: A neural network model built using Keras' Sequential API, designed to capture complex patterns in the data.

*Results:*

The performance of each model is summarized below:

### A tabular representation of the models' performances

| Model                    | Mean Absolute Error | Mean Squared Error | Root Mean Squared Error |
|--------------------------|---------------------|--------------------|-------------------------|
| Linear Regression        | 911.78              | 1503261.73         | 1226.08                 |
| Random Forest Regressor  | 88.74               | 38990.96           | 197.46                  |
| Support Vector Regression| 1064.01             | 2137533.53         | 1462.03                 |
| SVR after Grid Search    | 784.81              | 1555151.39         | 1247.06                 |
| Sequential DL Model      | 709.11              | 912725.29          | 955.37                  |


*Conclusion:*

Among the models evaluated, the Random Forest Regressor demonstrated the best performance with the lowest MAE, MSE, and RMSE values, indicating its effectiveness in predicting crime rates. The Sequential Deep Learning model also showed promise but did not outperform the Random Forest model. These findings suggest that ensemble methods like Random Forests are highly effective for this type of regression task.

