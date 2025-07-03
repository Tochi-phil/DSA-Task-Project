# DSA-Task-Project
Hi! I'm currently building my first Data Analytics portfolio as part of my training at DSA. This repo showcases hands-on projects using Excel, SQL, and Power BI, focused on data cleaning, analysis, and visualization.

## Project: Amazon Product Review Analysis

### Company Overview
Working as a Junior Data Analyst at RetailTech Insights, a company that provides e-commerce analytics solutions to sellers on platforms like Amazon. Your team has been
tasked with analysing product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement.

### Dataset Description
The dataset contains information scraped from Amazon product pages, including:
-  Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
Total Records: 1,465 rows TotalFields: 16 columns

### Analysis Tasks & Tools
The tool used for this task is MicroSoft Excel (Download here){https://www.microsoft.com/en/microsoft-365/excel?market=af}

   1. What is the average discount percentage by product category?
   2. How many products are listed under each category?
   3. What is the total number of reviews per category?
   4. Which products have the highest average ratings?
   5. What is the average actual price vs the discounted price by category?
   6. Which products have the highest number of reviews?
   7. How many products have a discount of 50% or more?
   8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 4.0, etc.)?
   9. What is the total potential revenue (actual_price × rating_count) by category?
   10. What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)?
   11. How does the rating relate to the level of discount?
   12. How many products have fewer than 1,000 reviews?
   13. Which categories have products with the highest discounts?
   14. Identify the top 5 products in terms of rating and number of reviews combined.

### Dashboard Creation
Using the cleaned dataset and pivot outputs, build an Excel dashboard.


  - The file was downloaded, and MS Excel was used to inspect the dataset.
   - To check for blanks for numbers and text Countblank function was used. The dataset cleaning continued by removing some columns that were not needed in the analysis.
    - The TextAfter function was used to shorten the long product category descriptions, and the new column for the short description is labelled Category_extc.
     - The Price bucket column was gotten by actual_price - discounted_price = price bucket
     - Potential revenue by category = actual_price x rating_count
      - Average discount percectage by product category is 48%
       - Tota number of reviews per category is 26,767,877
        - Smartphones, SmartTelevision, InstantWater heater, Hand Blenders etc have the highest average rating.
         - HDMI Cables, Headphones, Smartphones etc have highest number of reviews.
         - 751 products have discount of 50% and more
           - 4 products have a 3.0 rating, 181 products have 4.0 rating.
            - The higher the rating lower the discounted price, and the lower the rating the higher the discounted price this is to encourage consuner to buy.
             - 320 products have fewer than 1,000 reviews 
              - Traditional Laptops, SmartTelevisions and Smartphones have the highest discounts




 


