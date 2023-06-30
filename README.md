# SUPERMARKET-SALES-PREDICTION: Statistical Analysis and Predictive Modeling 

# CHAPTER 1

## ABSTRACT

The goal of this project is to forecast supermarket sales using a dataset that contains a variety of data points, including 'City', 'Customer type', 'Gender', 'Product line', 'Unit price', 'Quantity', 'Date', 'Payment', 'Total', 'gross income'. The project's goal is to determine the variables that have the greatest impact on supermarket sales and to develop a model that can properly predict sales growth. The project comprises feature selection, data exploration and visualization, and machine learning algorithms including logistic and linear regression. Stakeholders will receive effective interpretation and communication of the analyses' findings. The final objective is to offer insights that can boost sales.

## INTRODUCTION

The supermarket sales analysis is a study that involves the exploration and evaluation of sales data from a retail supermarket. In this analysis, we examine various factors that could affect the sales of a supermarket, including customer demographics, product line, payment methods, and others. We also aim to gain insights into the relationship between different variables in the dataset, such as the correlation between unit price, quantity, total sales, and gross income. Through statistical tests like t-test, ANOVA and chi-square, we aim to identify any significant differences in sales across different customer groups and product lines. Finally, we use machine learning techniques like feature selection, logistic and linear regression to predict future sales and optimize business strategies. The insights gained from this analysis could help supermarkets better understand their customers and make data-driven decisions to improve sales and customer satisfaction.

# CHAPTER 2

## DATA DESCRIPTION

The growth of supermarkets in most populated cities are increasing and market competitions are also high. The dataset is one of the historical sales of supermarket company which has recorded in 3 different branches for 3 months data.The dataset consists of 5 numerical values and 5 categorical value.

# CHAPTER 3

## METHODOLOGY

T-Test: The t-test is a statistical test used to compare the means of two groups and determine if they are significantly different from each other. In this project, a t-test was performed to compare two samples and assess if there was a significant difference in total sales based on gender.
ANOVA: Analysis of Variance (ANOVA) is a statistical test used to determine if there are significant differences between the means of three or more groups. In this project, an ANOVA test was conducted to examine the relationship between city and total sales. The goal was to determine if there was a significant difference in total sales across different cities.
Chi-Square: Chi-Square test is used to analyze the association between categorical variables. In this project, a chi-square test was employed to evaluate if there was a significant relationship between gender and customer type.
Linear Regression: Linear regression is a statistical technique used to model the relationship between a dependent variable and one or more independent variables. In this project, linear regression was applied to assess the relationship between various factors (such as gender) and the total sales. The analysis aimed to determine if gender was a good predictor of total sales.
Resampling Methods: Resampling methods such as bootstrapping and cross-validation were employed to assess the performance and reliability of the predictive models.
Bootstrapping was used to estimate the mean and confidence interval of the 'Total' column, providing insights into the overall sales. Cross-validation analysis was performed to evaluate the goodness of fit of the model, using R2 scores to assess its accuracy and reliability.
Linear Model Selection and Regularization: Ridge regression and Lasso regression are regularization techniques used to prevent overfitting in linear regression models. Ridge regression introduces a penalty term to shrink the coefficients, while Lasso regression pertorms both coefficient shrinkage and feature selection. In this project, both techniques were used to select the best hyperparameters and assess the models' performance in predicting future sales.
Moving Beyond Linearity: Polynomial regression, piecewise cubic spline, and piecewise linear spline were employed to capture non-linear relationships between variables. Polynomial regression allowed for fitting higher degree polynomial functions, while piecewise cubic spline and piecewise linear spline aimed to capture non-linear patterns and changes in the relationship between variables.

# CONCLUSION

In this project, we conducted a comprehensive analysis of a dataset containing information about supermarket sales. Our goal was to identify the variables that have the greatest impact on supermarket sales and develop a predictive model to forecast sales growth.
We started by exploring and visualizing the data, examining various factors such as customer demographics, product line, and payment methods. We performed statistical tests including t-test, ANOVA, and chi-square to determine if there were any significant differences in sales across different customer groups and cities.
The results of our analysis revealed that gender and city did not have a significant relationship with total sales. Additionally, there was no statistically significant relationship between gender and customer type.
We then applied machine learning techniques such as linear regression, ridge regression, and lasso regression to predict future sales. The linear regression model showed a perfect fit with an extremely low mean squared error, indicating its ability to predict the total sales accurately. Among the regularization models, the Lasso regression model performed better, explaining around 88.44% of the variance in the target variable.
Furthermore, we explored non-linear relationships using polynomial regression, piecewise cubic spline, and piecewise linear spline. The results indicated that a polynomial degree of 8 or less was the best choice, and there was a positive correlation between gross income and total sales.
Overall, our analysis can provide valuable insights for stakeholders in the supermarket industry. We discovered that gender and city were not significant factors affecting sales, while customer type had no association with gender. Our predictive models can assist in forecasting future sales, and the non-linear analysis revealed the nature of the relationship between gross income and total sales.
By leveraging these findings, supermarkets can make data-driven decisions to optimize their business strategies, improve customer satisfaction, and boost sales growth in a highly competitive market.

