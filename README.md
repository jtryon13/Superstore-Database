# Superstore-Database
Sorted data by price, category, and specific category trends.

Select *
From superstore
Order by price desc; 

Select Sum (price), category
From Superstore
Group By category;

Select Count (item_name), category
From Superstore
Group By category;

Select Distinct (item_name),price
 From Superstore
 Where Category = 'Kitchen Supplies'
Group by price; 
