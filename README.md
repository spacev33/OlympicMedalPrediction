# Olympic Medal Prediction using Linear Regression

**Author:** Evelina SPAC

## Project Description

This project aims to predict the number of medals each country will win in the Olympics using a linear regression model with two parameters: the number of athletes and the previous medals won. We explore historical Olympic data to build and evaluate the model's performance.

## Data

The data used in this project is sourced from Kaggle: [https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)

We utilize two datasets:

* **teams.csv:** Contains team-level data, including country, year, number of athletes, previous medals won, and the target variable - the number of medals won in a given year.
* **athlete_events.csv:** This is the original athlete-level data, which we do not directly use in this project but is the source for the aggregated team-level data.

## Results

* **Model Performance:** The linear regression model achieved a mean absolute error of **3.29** on the test data. This indicates that **on average, we are are whithin 3.3 medals of how many medals a team actually won in the Olympics.**

* **Insights:** The model suggests that the number of athletes and previous medals won are significant predictors of Olympic medal success. Countries with more athletes and a history of winning medals tend to perform better in future Olympics.

## Conclusion

This project demonstrates the application of linear regression to predict Olympic medal counts. While the model's accuracy can be further improved, it provides valuable insights into the factors that contribute to a country's Olympic success.

## Future Work

* Exploring and incorporating additional features, such as training resources, etc. could enhance the model's predictive power.
* **Model Selection:** Experimenting with other regression models, such as polynomial regression or ridge regression, may lead to improved performance.
* **Data Updates:** Regularly updating the data with results from recent Olympics will ensure the model's relevance and accuracy.
