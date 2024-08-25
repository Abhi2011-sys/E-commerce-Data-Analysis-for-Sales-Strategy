# E-commerce-Data-Analysis-for-Sales-Strategy
In their annual sales review meeting, Kmart, one of the largest online retailers in the US, must decide on their sales strategy for 2020 based on insights from the 2019 sales data.
Business Problem Statements
Observations on the following are made:

What was the best month for sales?
Which city had the highest number of sales?
Best time to display advertising to maximize sales?
Best-selling product & Why?
What products are most often sold together?
Dataset
Data belongs to Kmart: A leading online retailer in the US
Time Period :  January 2019  -  December 2019
Unique Products:  19
Total Orders :  178,437
Cities :  9
KPI’s : Total Sales, Total Products Sold
Data Analysis Using Python
Loaded data for each month and created a data frame using Pandas.
For 2019 sales, an aggregated dataset was created by concatenating multiple datasets together.
Data handling for null values and junk data.
Preprocessed data to make a filtered dataset.
Business problem analysis and their solutions. (visualizations using matplotlib and seaborn library)
What was the best month for sales?
Create a new dataset with all records grouped by month
Plot the graph using matplotlib

Which city had the highest number of sales?
Extract the “Purchase Address” column containing the city information into a separate dataframe.
Group this dataframe by City and each group will have a sum of all the sales in that city.
Visualize the graph using matplotlib

Best time to display advertising to maximize sales?
Extract the Hours from the Order Date.
Group the data by Hours and depict the graph using matplotlib.

Best-selling product & Why?
Determine the sum of the "Quantity Ordered" by grouping by "Product".
Visual representation of the Quantity Ordered for each Product.

Let us also see a graphic representation of the Prices for each product grouped by Product.

What products are most often sold together?
Group the product by the Order ID to know which products were sold together.
Find the duplicate values of the “Order ID” by using the .duplicated() method.
Using .transform() method, create a new column called "Grouped" to combine values from multiple rows into one.
Drop the duplicates created when products were merged for each order ID.
Display the top 5 products most often sold together.


Tools Used
Jupyter Notebook Python Pandas Matplotlib Plotly
