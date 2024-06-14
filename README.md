# Online-store-research
Project Description
As a test assignment, you are to explore data from an online gift shop. The shop frequently ships items by mail and works with both wholesale and retail customers. You should use Python for data analysis to demonstrate your ability to independently solve tasks related to data exploration, customer segmentation, and hypothesis testing.

## Project Execution Instructions

## Step 1: Data Acquisition, Inspection, and Merging

    Load the data from CSV files into dataframes.
    Examine the general information about the dataframes.
    Check for missing values and decide on how to handle them.
    Check for duplicates and decide whether to remove them.
    Review data types in each column and convert types if necessary.
    Verify the consistency of identification numbers.
    Combine information from all dataframes into one.

## Step 2: Preprocessing and Initial Exploratory Data Analysis

    Identify outliers and anomalies in the 'price' and 'quantity' columns. Calculate the total cost of each item in the dataset and decide whether to retain or discard suspicious data.
    Examine the 'order_id', 'customer_id', 'name_clust', 'entry_id', and 'country_id' columns.
    Analyze the completeness of data by examining the timestamp of records. Count the number of days without sales each month. Select a period containing the majority of data for further analysis and work only with relevant data.

## Step 3: Metric Calculation

    Evaluate the number of orders and the number of unique customers by hours and days of the week. Plot graphs and draw conclusions about the presence of cyclicity in customer activity.
    Calculate the average daily revenue per customer and the number of unique customers per month. Draw conclusions about the presence or absence of seasonality, if possible.
    Calculate the stickiness factor for the second and third quarters of 2019.
    Create a profile for each customer, including the number of orders, the date of the first and last order, the total amount of all orders, the average order price, and other metrics of your choice.
    Separate customers into repeat and non-repeat groups based on the presence of repeat purchases. Calculate and evaluate the average metrics for each group based on customer profiles, where possible.

## Step 4: Perform RFM Segmentation of Customers

    Segment customers into groups using the RFM methodology.
    Evaluate the resulting groups, identifying similarities and differences.
    Formulate business recommendations for interacting with these segments, accompanied by appropriate graphs and tables.

## Step 5: Test Statistical Hypotheses

    Compare the proportions of repeat and non-repeat customers for the second and third quarters of 2019 using an appropriate statistical test.
    Compare the average checks in countries with 'country_id' equal to 3, 6, and 24. Based on statistical tests, conclude whether the average checks in these countries differ.
    Formulate and test your own hypothesis.

## Step 6: Write a General Conclusion
    Describe the results obtained and provide a final conclusion of the study.

## Step 7: Conduct Additional Research (optional)
    Investigate which products are most frequently purchased together.
