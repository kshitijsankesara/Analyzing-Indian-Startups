# Analyzing-Indian-Startups

IST 652: Scripting for Data Analysis

For my project, I analyzed the Indian Startup Ecosystem data from Kaggle (https://www.kaggle.com/sudalairajkumar/indian-startup-funding). I aim to find out which factors contributed to the funding amount, the important investors, type of startups, and which field gets the most fundings. The data consisted of *10 variables.* I also aim to understand the relation between fundings and location of the startup and other factors.

**Data Preprocessing:**
1. Removed a couple of columns that were not significant.
2. Checked null values.
3. Checked data types of each column and corrected some of them.
4. Renamed all the columns
5. Created new columns based on the data.
6. Replace strings of data

From our analysis, we answered multiple significant business questions.

**Business Questions:**
1. Which startup received the highest funding amount?
2. Which City recorded the most funding amount?
3. How funding amount fluctuated over the years?
4. Which industry is favorable for Fundings?
5. Who are the top Investors?
6. Which investment type receives the major fundings?


**Regression Model:**
We implemented a multiple regression model to understand the relationship between multiple variables. We build our model using the training data (80%) and later tested it on the testing data (20%). We evaluated our model using the Mean Absolute Error. We also plotted the predicted values with our actual values.

**Time-Series Model:**
We build a time series model for analyzing and forecasting the funding amount concerning time.

**Libraries: Pandas, NumPy, Seaborn, matplotlib, sklearn, wordcloud**

**Language: Python**
