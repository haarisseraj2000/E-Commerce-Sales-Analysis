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

<img width="334" alt="192509661-634c5a5b-17a7-4307-974c-bfe12592ee48" src="https://github.com/haarisseraj2000/E-Commerce-Sales-Analysis/assets/83971005/71aefc3f-2e72-46dc-a2f8-158122a119e8">


### Which city had the highest number of sales?
1. Extract the “Purchase Address” column containing the city information into a separate dataframe.
2. Group this dataframe by City and each group will have a sum of all the sales in that city.
3. Visualize the graph using matplotlib

<img width="343" alt="1 1" src="https://github.com/haarisseraj2000/E-Commerce-Sales-Analysis/assets/83971005/ace516ae-979b-4437-85e8-a7aa2a66571b">

### Best time to display advertising to maximize sales?
1. Extract the Hours from the Order Date.
2. Group the data by Hours and depict the graph using matplotlib.

<img width="328" alt="1 2" src="https://github.com/haarisseraj2000/E-Commerce-Sales-Analysis/assets/83971005/321f279a-8469-406a-b119-5a1a457ecad1">

### Best-selling product & Why?
1. Determine the sum of the "Quantity Ordered" by grouping by "Product".
2. Visual representation of the Quantity Ordered for each Product.






<img width="355" alt="1 3" src="https://github.com/haarisseraj2000/E-Commerce-Sales-Analysis/assets/83971005/d8dc2bcb-50f7-4d0f-925c-a3ce1dec806b">

.. Let us also see a graphic representation of the Prices for each product grouped by Product.

<img width="349" alt="1 4" src="https://github.com/haarisseraj2000/E-Commerce-Sales-Analysis/assets/83971005/625a8d3a-4130-4a06-bbee-ff469c6aff45">


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

   

