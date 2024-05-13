# Calory Intake Prediction Analysis - Regression

# 1. Dataset Overview
Dataset source: https://www.kaggle.com/datasets/animeshmahajan/fitbit-dataset

```
Features:
	- Calories: Information about the number of calories consumed by the individual. This data can give an overview of the person's dietary habits and energy intake.

	- Steps: The number of steps taken by the person each day. This data is useful to track daily physical activity and overall movement patterns.

	- Sleep Data: Details about the individual's sleep patterns, including sleep duration and sleep quality. This information can reveal the person's sleep habits and help identify potential sleep-related issues.

	- Intensity Activity: Information about the intensity of physical activities performed. It may include data on activities like walking, running, cycling, or other exercises, indicating the level of physical exertion.

	- Logged Weight: The recorded body weight of the individual at different points in time. Tracking weight changes can offer insights into weight management progress and health goals.

	- Calories Burned for Activities: Data on the number of calories burned during various physical activities and exercises. This information can be crucial in understanding the effectiveness of different workouts and the overall impact on calorie expenditure.
```
The comprehensive nature of this data makes it a valuable resource for conducting in-depth analysis of the individual's health and fitness trends over the course of the year. It can be used for various purposes, such as monitoring health progress, identifying patterns in activity levels, and making informed decisions to improve overall well-being and lifestyle.

# 2. Technical Requirements
## Libraries
<li>pandas
<li>numpy
<li>matplotlib
<li>seaborn
<li>scikit-learn

## Algorithms
<li>Linear Regression(Ridge Regression)
<li>Polynomial Features
<li>Grid Search CV
<li>K-Fold Cross Validation


# 3. Methodology
A linear regression model was built to predict caloric intake based on the selected attributes. The dataset was preprocessed, and feature scaling was applied to ensure optimal model performance. Cross-validation and grid search techniques were employed to tune hyperparameters and evaluate model performance.

# 4. Results
The final model achieved a high R-squared score, indicating excellent predictive capabilities. The analysis provides valuable insights into the individual's dietary habits, physical activity levels, and overall health tracking.