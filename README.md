# The impact of COVID-19 on housing price
<div align="center">
  <sub> Made with ❤︎ by
  <a href="https://www.linkedin.com/in/natalia_chirtoca/">Natalia Chirtoca</a> 
</div>


<!-- primary badges -------------------------------------->
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
![Python](https://img.shields.io/badge/python-v3.8+-blue.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<img align="right" src="src/2C5L.gif" height="200">

## 🌻 Motivation
In this project we are going to carry out an analysis of the evolution of a house prices dataset. 
<!-- <p align='center'>
     ![gif](src/2C5L.gif)
</p>
<br/> -->

## ⚛ Process
For the development of this project we will be using the CRISP-DM methodology, which include the following stages. 
 - Business Understanding 
 - Data Understanding 
 - Prepare Data 
 - Data Modeling 
 - Evaluate the Results 
 - Deploy

### ⚡ Business Understanding
What are the best states to invest in real estate?
Is Now a Good Time to Buy a House?
Which feature has more effect in increasing the price of the house?

## ⛳ Installation
Libraries required:
- Python 3
- Scikit-learn
- matplotlib
- Seaborn

Because of github limitations to big dataset files, download the file from [here](https://drive.google.com/file/d/1CoE7MhIeW89lvu6XhYiPBkb8RRm9eo7O/view?usp=sharing)

## 📙 Dataset
Index(['month_date_yyyymm', 'postal_code', 'zip_name', 'flag',
       'median_listing_price', 'median_listing_price_mm',
       'median_listing_price_yy', 'active_listing_count',
       'active_listing_count_mm', 'active_listing_count_yy',
       'median_days_on_market', 'median_days_on_market_mm',
       'median_days_on_market_yy', 'new_listing_count', 'new_listing_count_mm',
       'new_listing_count_yy', 'price_increased_count',
       'price_increased_count_mm', 'price_increased_count_yy',
       'price_reduced_count', 'price_reduced_count_mm',
       'price_reduced_count_yy', 'pending_listing_count',
       'pending_listing_count_mm', 'pending_listing_count_yy',
       'median_listing_price_per_square_foot',
       'median_listing_price_per_square_foot_mm',
       'median_listing_price_per_square_foot_yy', 'median_square_feet',
       'median_square_feet_mm', 'median_square_feet_yy',
       'average_listing_price', 'average_listing_price_mm',
       'average_listing_price_yy', 'total_listing_count',
       'total_listing_count_mm', 'total_listing_count_yy', 'pending_ratio',
       'pending_ratio_mm', 'pending_ratio_yy'],
      dtype='object')

 - Median Listing Price	 -  The median listing price within the specified geography during the specified month.
 - Median Listing Price M/M	 - The percentage change in the median listing price from the previous month.
 - Median Listing Price Y/Y	 - The percentage change in the median listing price from the same month in the previous year.
 - Active Listing Count	 - The count of active listings within the specified geography during the specified month. The active listing count tracks the number of for sale properties on the market, excluding pending listings where a pending status is available. This is a snapshot measure of how many active listings can be expected on any given day of the specified month.
 - Active Listing Count M/M	 - The percentage change in the active listing count from the previous month.
 - Active Listing Count Y/Y	 - The percentage change in the active listing count from the same month in the previous year.
 - Days on Market	 - The median number of days property listings spend on the market within the specified geography during the specified month. Time spent on the market is defined as the time between the initial listing of a property and either its closing date or the date it is taken off the market.
 - Days on Market M/M	- The percentage change in the median days on market from the previous month.
 - Days on Market Y/Y	- The percentage change in the median days on market from the same month in the previous year.
 - New Listing Count	- The count of new listings added to the market within the specified geography. The new listing count represents a typical week’s worth of new listings in a given month. The new listing count can be multiplied by the number of weeks in a month to produce a monthly new listing count.
 - New Listing Count M/M	- The percentage change in the new listing count from the previous month.
 - New Listing Count Y/Y	- The percentage change in the new listing count from the same month in the previous year.
 - Price Increase Count	- The count of listings which have had their price increased within the specified geography. The price increase count represents a typical week’s worth of listings which have had their price increased in a given month. The price increase count can be multiplied by the number of weeks in a month to produce a monthly price increase count.
 - Price Increase Count M/M	- The percentage change in the price increase count from the previous month.
 - Price Increase Count Y/Y	- The percentage change in the price increase count from the same month in the previous year.
 - Price Decrease Count	- The count of listings which have had their price reduced within the specified geography. The price decrease count represents a typical week’s worth of listings which have had their price reduced in a given month. The price decrease count can be multiplied by the number of weeks in a month to produce a monthly price decrease count.
 - Price Decrease Count M/M	- The percentage change in the price decrease count from the previous month.
 - Price Decrease Count Y/Y	- The percentage change in the price decrease count from the same month in the previous year.
 - Pending Listing Count	- The count of pending listings within the specified geography during the specified month, if a pending definition is available for that geography. This is a snapshot measure of how many pending listings can be expected on any given day of the specified month.
 - Pending Listing Count M/M	- The percentage change in the pending listing count from the previous month.
 - Pending Listing Count Y/Y	- The percentage change in the pending listing count from the same month in the previous year.
 - Median List Price Per Sqft	- The median listing price per square foot within the specified geography during the specified month.
 - Median List Price Per Sqft M/M	- The percentage change in the median listing - price per square foot from the previous month.
 - Median List Price Per Sqft Y/Y	- The - percentage change in the median listing price - per square foot from the same month in the previous year.
 - Median Listing Sqft	- The median listing square - feet within the specified geography - during the specified month.
 - Median Listing Sqft M/M	- The percentage change in--   the median listing square feet from the previous month.
 - Median Listing Sqft Y/Y	- The percentage change in the - median listing square feet from the same month in the previous year.
 - Avg Listing Price M/M	- The - percentage change in the av- erage listing pre from the previous month.
 - Avg Listing Price Y/Y	- The - perceage change in the - average listing price from the same month in the previous year.
 - Total Listing Count	- The - total of both active listin- gs and pending listings within the specified geography during the specified month. This is a snapshot measure of how many total listings can be expected on any given day of the specified month.
 - Total Listing Count M/M	- - The percentage change in - the total listing count from the previous month.
 - Total Listing Count Y/Y	- - The percentage change in the - total listing count from the same month in the previous year.
 - Pending Ratio	- The ratio - of the pending listing count - to the active listing count within the specified geography during the specified month.
 - Pending Ratio M/M	- The change in the pending ratio from the previous month.
 - Pending Ratio Y/Y	- The change in the pending ratio from the same month in the previous year.

## Ⓜ️ Medium Blogpost
You can see the complete article [here](https://medium.com/@chirtoca.natalia/covid-19-and-real-estate-b33321491ce6)

## 🙏 Licensing, Acknowledgements
This project is published in 2021 under [MIT](https://es.wikipedia.org/wiki/Licencia_MIT) license.
Must give credit to Kaggle for the data.
