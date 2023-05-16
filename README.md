# Video Game Advertising Campaign Analysis

This project aims to analyze the effectiveness of video game advertising campaigns by looking at the relationship between various marketing metrics such as cost, impressions, clicks, and sales. The goal is to understand how these metrics influence each other and subsequently optimize advertising strategy for better returns.

## Project Overview

The project follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology and is divided into several stages:

1. **Data Understanding and Preparation:** Synthetic data is generated to simulate an actual advertising dataset. This data includes fields like 'date', 'campaign', 'cost', 'impressions', and 'clicks', and is generated using random numbers and distributions that mimic real-world data. The 'sales' field is also synthesized based on a simple linear model of the other features, with some random noise added.

2. **Exploratory Data Analysis (EDA):** The dataset is then analyzed using descriptive statistics and visualization tools to identify patterns, relationships, and outliers. This step provides insights into the general trends and correlations in the data.

3. **Modeling:** A linear regression model is built using Scikit-Learn to predict sales based on cost, impressions, and clicks. The model is trained on a portion of the dataset and tested on the remaining data.

4. **Evaluation:** The model's performance is evaluated using the mean squared error metric. Further steps are taken to improve the model, such as feature engineering and hyperparameter tuning.

5. **Interpretation and Business Decisions:** Finally, the model's output is interpreted in a business context, and recommendations are made based on the findings.

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Installation

This project requires Python 3.x and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-Learn](https://scikit-learn.org/stable/)

## Conclusion

This project provides a framework for understanding and optimizing video game advertising campaigns. It highlights the importance of data analysis in making informed business decisions. The methods used here can be applied to real-world data to gain valuable insights into the effectiveness of advertising campaigns.
