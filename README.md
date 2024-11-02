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
  
  ![Screenshot 2024-11-02 194737](https://github.com/user-attachments/assets/1ba87cce-f3c8-4182-b294-9ab8e1dfa6f4)

  (b) Sales Summary
  
  ![Screenshot 2024-11-02 194753](https://github.com/user-attachments/assets/2a776fd6-b1a8-4b71-b8e2-7bf72c260d72)
  
  (c) Category: Subcategories and Category level insights on sales and profits on for different categories
  
  ![Screenshot 2024-11-02 194815](https://github.com/user-attachments/assets/3916cc9e-a9e2-4e43-b83f-96f74cda5020)
  
  (d) Sucategory: Product and Subcategories level insights on sales and profits on for different sub-categories
  
  ![Screenshot 2024-11-02 194837](https://github.com/user-attachments/assets/e18b54c1-446c-4444-8323-2a911e830218)
  
  (e) Region: Regional trends for sales and profit
  
  ![Screenshot 2024-11-02 195212](https://github.com/user-attachments/assets/c5a31351-29dc-4faf-a097-d4436781b78e)
  
  (f) Salesperson: Sales overview for a sales person
  
  ![Screenshot 2024-11-02 195228](https://github.com/user-attachments/assets/7164e8ad-f167-4347-91f7-683c5065200e)



# Snapshot of Dashboard (Power BI Service)


# Insights


