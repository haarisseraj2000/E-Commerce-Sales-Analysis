# E-Commerce-Sales-Analysis
Kmart, one of the largest online retailers in the US, must decide on their sales strategy for 2020 based on insights from the 2019 sales data.

This project focuses on generating key insights regarding Kmart's sales for each month of 2020. The data will be used to assist Kmart's sales team in fine-tuning sales strategies as the year progresses.

## Business Problem Statements

1. What was the best month for sales?
2. Which city had the highest number of sales?
3. Best time to display advertising to maximize sales?
4. Best-selling product & Why?
5. What products are most often sold together?

### Dataset 

. Data belongs to Kmart: A leading online retailer in the US
. Time Period :  January 2019  -  January 2020
. Unique Products:  19
. Total Orders :  178,437
. Cities :  9
. KPI’s : Total Sales, Total Products Sold

#### Data Analysis Using Python
1. Loaded data for each month and created a data frame using Pandas.
2. For 2019 sales, an aggregated dataset was created by concatenating multiple datasets together.
3. Data handling for null values and junk data.
4. Preprocessed data to make a filtered dataset.
5. Business problem analysis and their solutions. (visualizations using matplotlib and seaborn library)

##### What was the best month for sales?
. Plot the graph using matplotlib




### Which city had the highest number of sales?
1. Extract the “Purchase Address” column containing the city information into a separate dataframe.
2. Group this dataframe by City and each group will have a sum of all the sales in that city.
3. Visualize the graph using matplotlib



### Best time to display advertising to maximize sales?
1. Extract the Hours from the Order Date.
2. Group the data by Hours and depict the graph using matplotlib.



### Best-selling product & Why?
1. Determine the sum of the "Quantity Ordered" by grouping by "Product".
2. Visual representation of the Quantity Ordered for each Product.







.. Let us also see a graphic representation of the Prices for each product grouped by Product.




# Tools Used
Jupyter|Notebook|Python|Pandas|Matplotlib|Plotly

Jupyter Notebook is used as IDE.
Among the Python libraries, Pandas is used for handling and preprocessing data.
Plotly, Seaborn, and Matplotlib are used for visualizing plots.
For more details, please go through the Jupyter Notebook attached above.

# Conclusion

The analysis above clearly illustrates that month 12 (December) boasts the maximum sales in 2019 with roughly $9,226,886.
According to the graph, San Francisco has the largest number of sales.
The optimum time to display advertising to increase the probability of buyers purchasing the product/s is shortly before 12 pm and/or right before 7 pm.
The top selling product is 'AAA Batteries (4-pack)'. The top selling products seem to have a correlation with the price of the product. The cheaper the product, higher the quantity ordered and vice versa.

   

