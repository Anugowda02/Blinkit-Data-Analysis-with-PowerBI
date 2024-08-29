# Blinkit-Data-Analysis-with-PowerBI
This Repository Contains all necessary information about my power BI projects like the dataset used and the pbix file.



# Blinkit - Dashboard


## Problem Statement

This dashboard helps to conduct a comprehensive analysis of blinkit sales performance, customer satisfaction,and inventory distribution to identify key insights and oppurnities for optimization using various kpi's and visualization in power BI.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : Replace the values ,created and optimized data relationship for effective analysis.
- Step 6 : Implemented DAX formulas for metrices like Total sales and Average Rating.
- Step 7 : Dashboard Layouting,charts development and formatting.
- Step 8 : Report development and insights generation.
 
## Page.1 of the repot: 
- Overwiew
 ![snap1](https://github.com/user-attachments/assets/23c073ad-fd0e-45ba-af06-83c630801425)

## Page.2 of the repot: 
- Average sales based on the loaction.

 ![Snap2 ](https://github.com/user-attachments/assets/81679ba8-a659-4a9d-8e13-4b507970853c)
        
## Dax Expression
- Total sales = sum('Blinkit Grocery Data'[sales])
- Average sales= Average('Blinkit Grocery Data'[sales])
- No of items = CountRows('Blinkit Grocery Data')
- Avg Rating = Average('Blinkit Grocery Data'[sales])

## Page.3 of the repot: 
- Total number of Average Rating.
 
 ![Snap3](https://github.com/user-attachments/assets/4333bc5c-4e4e-4d9c-af16-70a71f989853)


 ## Insights

- Fruits and Vegetables has the highest sales of 178k 
  and sea food has the lowest sales.
- Snacks foods has second highest of 175k sales.
- The funnel chart divides the sales based on the 
  location type.

   Tier 1: 336.40%

   Tier 2: 393.15%

   Tier 3: 472.13%

 ## Metrices
 - The total number of sales transaction made is 1.20M
   sales.
 - The average customer rating out 5 is 3.9
 - The total number of items available for sales is 8k.






 
 
 
