# Retail-Store-Analysis
## PROJECT OBJECTIVE:
The Store wants to create an annual sales report. So that, the owner of the store can understand their customers and grow more sales.
## METRICS:
• Compare total sales and order count.   
• Identify the highest sales and order month.  
• Determine if men or women purchase more.  
• Analyse order statuses (Completed, Pending, Cancelled, Refunded).  
• Top 5 states that contribute to the sales.  
• Relation between age and gender based on orders.  
• Identify the highest revenue generating sales channel.  
• Highest selling Product category.  
• Best day of the week with highest sales.  
## DATA CLEANING:
• Checked raw data for duplicates, null values, missing values and inconsistencies.  
• Fixed the Gender column by changing “M” and “MEN” to Men, and “W”,” WoM”, “Wowen” to Women in a new column Gender2 using IF-OR function.  
• Cleaned the Qty column by alphabetical numbers like “one” and “two” into numerical values (1,2) using IF function in a new column Qty.  
• Made sure the columns Category, Ship-State and Ship-Country have the consistent formatting by using PROPER and UPPER functions to keep the text in the same case.  
## DATA TRANSFORMATION:
In this step we are creating few columns like Age-group, Month_name and Day of week which help us in the analysis.  
Age Group includes in one of the metrics to show the relationship between age and gender.  
Here, we create this column using IF-AND function by dividing age into four categories:  
• Less than 19 – Teens  
• Between 19 and 40 – Adults  
• Between 39 and 60 – Mid-age Adults  
• Above 59 – Seniors  
Month name and Day of week columns are created using “Text function” to extract the month and day from the date column in the text format.  
## DATA ANALYSIS:
- In this step we create pivot tables according to the metrics and create pivot charts to which helps in deep analysis and insights.  
- Nine pivot tables were created to analyse and identify insights focusing on relationship between sales and other factors such as gender, orders in different months, top states and countries. Orders status, orders on different channels, orders and age comparison were also performed.  
In the next step, Created Dashboard merging all pivot tables into one dashboard and inserted slicer to make dashboard more interactive and dynamic.  
Added four slicers – Day of week, Category, Channel and Month.  
## INSIGHTS:
• February and march are the peak months for highest orders and sales activity.  
• Women show a higher likelihood to buy more products with 69% of total sales.  
• The top five states contributing to sales are Maharashtra, Karnataka, Uttar Pradesh, Telangana, and Tamil Nadu.  
• The Adult age group is the most significant contributor, representing approximately 50% of total sales.  
• Amazon, Flipkart, Myntra are the primary sales channels, contributing to about 80% of the total sales.  
• The maximum orders with 92% of orders are in a delivered status, reflecting effective fulfilment processes.  
• The highest selling category is Set which has 39% orders of total orders.  
• Tuesday and Sunday are considered as best days of the week for sales activity.  
## CONCLUSION:
Based on our data analysis, we recommend the following strategies for sales growth of the store:  
- Target Women customers within the 20-39 age group living in Maharashtra, Karnataka, Uttar Pradesh.  
- Focus on Amazon, Flipkart, and Myntra as primary sales channels and invest in promotional activities in these platforms.  
- Implement targeted ad campaigns, offers and coupons to attract and retain customers.  
