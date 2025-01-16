# Analysis-of-Myntra-Apparel
This repository is a analysis of Myntra apparel data using Excel. This project involves data cleaning, exploring pricing trends, discounts, and customer ratings, and visualizing insights through charts and pivot tables. Key techniques include advanced Excel functions like VLOOKUP, INDEX/MATCH, and Power Query for data transformation.

Problem Statement:
You are working at Myntra, a leading online fashion retailer. The management has asked you to analyze a dataset of various apparel items to gain insights into pricing, discounts, ratings, and available sizes.

Dataset Link:
https://drive.google.com/file/d/1CDaWFvkccjdUw1E_gipTKOfMqiHNhNQL/view

Project Questions
A. Data Cleaning and Preparation
Check for duplicate values in your dataset and remove them.
Standardize the "DiscountOffer" column to a single format, ensuring all values are uniform.
Identify rows where both "DiscountPrice" and "DiscountOffer" are null and fill the "DiscountPrice" with the average discount price of the respective category.
Replace all null values in the "SizeOption" column with the text "Not Available."
B. Data Analysis
Calculate the overall average original price for products with ratings greater than 4.
Count the number of products with a discount offer greater than 50% OFF.
Count the number of products available in size "M."
Create a new column to label the products as "High Discount" if the discount offer is greater than 50% OFF, otherwise label them as "Low Discount."
C. Data Retrieval and Lookup
Use VLOOKUP/XLOOKUP to find the product brand, price, and rating of the product with Product_id "11226634".
Find the "DiscountPrice" for the product with the Product ID "6744434" using the INDEX and MATCH functions.
Utilize nested xlookup to find any column’s detail of a product with it’s product id.
