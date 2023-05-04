# Wind Power Prediction Model

## Executive Summary
Renewable energy is becoming more important every day. Specifically, using wind turbines is one of the most efficient and clean renewable energy sources. However, understanding where and when wind turbines are most efficient is incredibly important for companies to make a profit. This project explores how we took a dataset with a variety of features to create the most accurate machine learning model in order to predict how much power a wind turbine will produce.

## Objective
The objective of this project is to design a machine learning model that accurately predicts how much power a wind turbine will produce. To achieve this, we will follow several steps, including loading and cleaning the data, visualizing the data, and selecting the most relevant features for the model.

## Solution
We trained three different machine learning models to find the one that produces the best results: the Gradient Boosting Regressor, the Random Forest Regressor, and the K-Nearest Neighbors Regressor. All three models used GridSearchCV to optimize their hyperparameters and were evaluated based on their mean absolute error and R2 value. The Gradient Boosting Regressor was selected as the final model because it outperformed the other two models in all metrics and was less prone to overfitting. Additionally, it has reasonable scalability, making it a good option for managing more data in the future.

## Limitations and Future Improvements
One limitation of our dataset is that it only includes one year of data from one location. Wind patterns can change in different areas of the world, and the time of year and day can play a significant role in how much power is produced. Therefore, we recommend gathering data from different locations and years to diversify our dataset. 

Even though the Gradient Boosting Regressor is the best model we found, there are additional optimizations that can be performed. For example, additional hyperparameter optimization and analysis could be used to enhance the model's performance, leading to a more precise prediction and higher applicability for the final model.

## Getting Started

### Prerequisites
* Python 3
* Pandas
* Scikit-learn
* Seaborn

### Installation
1. Clone this repository
2. Install the required Python packages: pip install pandas scikit-learn seaborn

## Credits
This project was completed as part of a data science course at the University of Michigan. Contributors include: Brian Schneider, Myles Liss-Riordan, Seo Jun Yoon, Parth Patel
