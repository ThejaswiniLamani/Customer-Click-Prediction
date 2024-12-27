# Customer Click Prediction

## Objective

The objective of this project is to develop an effective machine learning model to predict customer clicks on advertisements. By analyzing key features such as:

- **Daily Time Spent on Site**
- **Age**
- **Area Income**
- **Daily Internet Usage**
- and other relevant factors

The model will provide valuable insights into customer behavior, ultimately improving the efficiency of ad campaigns and enabling better targeting of advertisements.

## Expected Outcomes

The envisioned machine learning model will serve as a predictive tool, offering actionable insights into the factors influencing customer clicks. This will help:

- Predict whether a user will click on an advertisement based on various features.
- Identify the most important features influencing customer behavior.
- Provide a solid foundation for data-driven decision-making.

This goes beyond predicting clicks and lays the foundation for strategic decision-making, positioning the company at the forefront of targeted and effective advertising.

## Data Description

The dataset contains 1000 rows and 10 columns with the following features:

- **Daily Time Spent on Site**: The amount of time a user spends on the website where the ad is displayed.
- **Age**: The age of the user who interacted with the advertisement.
- **Area Income**: The income level of the geographical area where the user is located.
- **Daily Internet Usage**: The amount of time, in minutes, a user spends on the internet daily.
- **Ad Topic Line**: The topic or content of the advertisement that the user interacted with.
- **City**: The city of residence of the user.
- **Male**: A binary variable indicating the gender of the user (1 for male, 0 for female).
- **Country**: The country where the user is located.
- **Timestamp**: The timestamp indicating when the user interacted with the advertisement.
- **Clicked on**: The target variable indicating whether the user clicked on the ad (1 for clicked, 0 for not clicked).

## Models Used

1. **Logistic Regression Model**: Achieved an accuracy of **0.97**.
2. **Decision Tree Model**: Achieved an accuracy of **0.95**.
3. **Random Forest Model**: Achieved an accuracy of **0.96**.

### Conclusion

The **Logistic Regression Model** works best for this project, providing the highest accuracy. 

Results
Logistic Regression Accuracy: 0.97
Decision Tree Accuracy: 0.95
Random Forest Accuracy: 0.96
