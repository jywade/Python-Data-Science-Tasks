# Python-Data-Science-Project

Set of real-world data science tasks completed using the Python Pandas library and visualized using Matplotlib.


### Tasks include:

* Data cleaning and preprocessing
* Exploratory data analysis
* Market basket analysis
* Statistical analysis
* Data visualization using various Matplotlib plots and charts

#### I use Python Pandas and Python Matplotlib to analyze and address business questions regarding sales data spanning 12 months. The dataset includes a breakdown of electronics store purchases by month, product type, cost, purchase address, etc.

I start by cleaning the data. Tasks during this section include:

* Drop NaN values from DataFrame
* Removing rows based on a condition
* Change the type of columns (to_numeric, to_datetime, astype)

#### Once the data is cleaned up our data a bit, I move to the data exploration section. In this section I explore 5 high level business questions related to the data:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

#### To answer these questions, I utilize different pandas & matplotlib methods. They include:

* Concatenating multiple csvs together to create a new DataFrame (pd.concat)
* Adding columns
* Parsing cells as strings to make new columns (.str)
* Using the .apply() method
* Using groupby to perform aggregate analysis
* Plotting bar charts and lines graphs to visualize our results
* Labeling our graphs

