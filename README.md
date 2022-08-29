![IronHack_Logo](https://user-images.githubusercontent.com/92721547/180667578-7208994e-3fdf-4006-8481-d0723b917662.png)

# Lab | Analytics with PowerBI

Refer to the data source [Marketing_Customer_Analysis.csv](https://github.com/ironhack-labs/lab-analytics-with-powerbi/tree/master/files_for_lab) for this lab

### Instructions 

1. Using Power Query, transform the "Effective_to_date" column to the date format MM/DD/YYYY and convert "Total_claim_amount" to currency with 2 decimal places.
2. Plot a bar chart showing the following aggregations by gender. (Keep same colors for each gender on all charts)
    - Average Monthly Premium 
    - Sum of Total Claim amount 
    - Number of open policies 
3. Using an appropriate chart show which policy type has the largest number of open complaints and filter this by marriage status.
4. Use maps to show which states have generated the most revenue. Highlight number of clients in these states on the tool tip and use response as a filter. 
5. Use a Treemap to show the number of clients in each education level and filter to clients with college degrees
6. Use tables to show the: 
    - Sales Channel by average Lifetime_values 
    - Marital status by number of policies 
7. Now let's analyze these tables further by creating the following crosstabs (Matrix): 
    - Sales Channel by Average lifetime value and number of clients per sales channel
    - Marital status with number policies open by gender 
