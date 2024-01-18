# Data-Science----Sales-Analytic

# Live Dashboard
  * Link : https://bit.ly/DashboardSalesPBI
![image](https://github.com/ifmankim/Data-Science----Sales-Analytic/assets/146405856/9db85555-3f11-41e8-a799-4e7d6abcaa4a)
# Use Case
  * Use Case Summary
    
  * Objective Statement:
    
    * Get business insight about what the best month for sales.
    * Get business insight about many product sold every month.
    * Get business insight about state with the highest number of sales.
    * Get business insight about the best time for advertising.
    * Get business insight about package sales.
      
  * Challenges:
    
    * Large size and different file csv.
    * Combining 12 csv file into 1 csv file.
    * Have a lot NAN Values.
      
  * Methodology / Analytic Technique:

    * Descriptive analysis
    * Graph analysis
    * Product Analysis

  * Business Benefit:
    
    * Help the Business Development Team to create product combinations based on products that are frequently purchased together.
    * Know what the best time for advertising.

  * Expected Outcome:
    
    * Know what the best month for sales.
    * Know about how many product sold every month.
    * Know what the best state with the highest number of sales.
    * Advertising time recomendation based on historical data.
    * Recomendation package sales.

# Business Understanding

  * An electronics store is a place that sells electronic goods to customers.
  * This case has several business questions that use data:
  * What the best month for sales ?
  * How many product sold every month ?
  * What the best state for pumping our sales ?
  * What the best time for advertising ?
  * What product we must sales as package ?

# Data Understanding

  * Elektronic Sales Transaction from 01 January 2019 to 01 Januari 2020
  * The dataset has 12 sheet with 6 columns and differents rows.
  * Data Dictionary:
    * Order ID: Invoice number assigned to each transaction.
    * Product: Product (item) name.
    * Quantity: The quantities of each product (item) per transaction.
    * UnitPrice: Product price per unit in USD ($).
    * Order Date: The day and time when each transaction was generated.
    * Address: The customer address.

# Data preparation

  * Code Used:
  * Python Version: 3.10.12
  * Packages: Pandas, Calendar, Matplotlib, Ittertools, Collections, Os

# Data Cleansing

  * When we combine 12 sheet into 1 sheet, there is included the header each of sheet. Then remove it.
  * After combining 12 sheet there is 545 NAN Values

# Recomendation

 * The highest sales occurred in December with sales amounting to 13% of all sales throughout the year. This coincides with the year-end holidays and Christmas. Therefore, business teams can increase sales this month by promoting new products to customers this month.
 * Given California's substantial 40% share in total sales, businesses may benefit from prioritizing and investing resources in this economically robust market.
 * Optimize advertising strategies by targeting the morning peak at 10 AM for lunchtime demand (11-12 noon) and capitalizing on the evening rush from 6-8 PM.
 * Leveraging customer buying patterns, bundling iPhones with Lightning cables and Google phones with USB-C cables in a single package not only boosts sales but also streamlines the purchasing process, enhancing customer satisfaction and fostering brand loyalty.


