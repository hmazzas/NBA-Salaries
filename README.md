# NBA Salaries
This project aims to develop a regression model to predict NBA players' salaries based on their regular season stats from the 2022/2023 season.

## Data Collection
The data was collected from two different sources. Firstly, the players' salaries (Cap Hit) were scraped from an HTML table on the ESPN website. Then, the "Balls Don't Lie" API was utilized to retrieve season stats for each player.

## EDA and Regression Model
After obtaining the dataset, exploratory data analysis (EDA) and descriptive statistics were performed to understand the structure and relationships within the data. Data preprocessing was conducted using the sklearn library, which involved standardization and splitting the data into training and test sets.

Several regression models were trained on the dataset, including Linear Regression, Ridge, Lasso, Elastic Net regularization, and Random Forest Regressor. Among these models, the Lasso model exhibited the highest R2-score and lowest RMSE, indicating its superior performance.
