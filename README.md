# Student Scores Prediction

This project demonstrates the implementation of Linear Regression using Python to predict student's scores based on the number of hours they studied. The dataset used contains the number of hours studied per day and the corresponding percentage scores. The goal is to understand the relationship between hours studied and percentage scores and to predict future scores based on this relationship.

## Project Overview

In this project, Linear Regression, a simple yet powerful statistical method, is used to model the relationship between the number of hours a student studies and their scores in exams. By doing so, we can predict a student's performance based on their study hours. The implementation covers data loading, visualization, model training, evaluation, and prediction.

## Dataset

The dataset `student_scores.csv` includes the following columns:
- `Hours`: Number of hours studied per day.
- `Scores`: Percentage scores obtained.

## Libraries Used

The following Python libraries are used in this project:
- math
- numpy
- pandas
- matplotlib
- scikit-learn

## Project Workflow

1. **Loading Data:** The dataset is loaded using the Pandas library, which provides easy-to-use data structures and data analysis tools.

2. **Data Visualization:** A scatter plot is created using Matplotlib to visualize the relationship between hours studied and percentage scores. This helps in understanding the distribution and correlation between the two variables.

3. **Training the Model:** The data is split into training and testing sets. A Linear Regression model is then trained using the training data. This model learns the relationship between the number of hours studied and the percentage scores.

4. **Model Evaluation:** The model's performance is evaluated using Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) metrics. These metrics are calculated for both training and testing data to understand how well the model is performing.

5. **Making Predictions:** The trained model is used to predict the score for a given number of study hours. For instance, it can predict the percentage score for a student who studies 9.25 hours per day. Additionally, a regression line is plotted to visualize the model's fit on the data.

## Results

The model provides an estimate of the percentage score based on the number of hours studied. The accuracy of the model is evaluated using RMSE, MSE, and MAE metrics, demonstrating its effectiveness in predicting student scores.

## For questions or feedback, please contact: javeriaf322@gmail.com



## Conclusion

This project showcases the implementation of a simple Linear Regression model to predict student scores based on study hours. The relationship between study hours and exam scores is effectively captured, and the model can be used for future predictions.
