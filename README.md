# Adventure-Sales-Dashboard

### Dashboard Link :

## Problem Statement

This dashboard helps the adventure sales, a bike manufacturer, analyse and understand their sales and profitaility by product, regions and categories. 
It helps the customer to understand the top selling and profitable products

Since, Sales has declined for last 4 quarters from 11.94 M to 5.54 million and overall profit margins are less than 1%.
The company needs to identify top loss making areas and focus on profit making products.
The company also needs to investigate the region and products where the sales and profit has taken a hit and create a recovery strategy.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present, except color in product table.
- Step 5 : Null values were replaced by N/A and Data types for all columns were checked and corrected. Calculated column that is profit was added in sales table
-              Profit = SUMX(Sales, Sales[sales] - Sales[cost])
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Measure was created i.e. Profit Margin
-             Margin = (SUMX(Sales,Sales[Profit])/SUMX(Sales,Sales[Sales]))*100
- Step 8 : The report consists of 7 pages which can traversed back and forth to drill down for specific insights. Only Summary pages are available for direct access. These pages consists of insights related to 

  (a) Overall Summary
  
  ![Screenshot 2024-11-02 233654](https://github.com/user-attachments/assets/9d713649-f11c-40d5-b9fc-27cb8b356127)

  (b) Sales Summary
  
  ![Screenshot 2024-11-02 233712](https://github.com/user-attachments/assets/98c6ad06-3776-40f8-a85f-ffda73723f6a)
  
  (c) Category: Subcategories and Category level insights on sales and profits on for different categories
  
  ![Screenshot 2024-11-02 233917](https://github.com/user-attachments/assets/b17ce898-b430-4ea3-8e14-67760dd737b2)
  
  (d) Subcategory: Product and Subcategories level insights on sales and profits on for different sub-categories
  
  ![Screenshot 2024-11-02 234011](https://github.com/user-attachments/assets/14015873-dbcf-4513-8a48-30d18f0a98c3)
  
  (e) Region: Regional trends for sales and profit
  
  ![Screenshot 2024-11-02 234130](https://github.com/user-attachments/assets/c14b3f56-50b1-4b8c-868c-ffcabbc67626)
  
  (f) Salesperson: Sales overview for a sales person
  
  ![Screenshot 2024-11-02 234258](https://github.com/user-attachments/assets/6e948ad7-e1f4-4554-861f-7fa04f51b5d3)


# Snapshot of Dashboard (Power BI Service)


# Insights


