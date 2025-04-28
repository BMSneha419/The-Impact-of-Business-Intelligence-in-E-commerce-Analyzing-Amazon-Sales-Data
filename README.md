This project involves an exploratory data analysis of Amazon sales data to derive business insights.The primary goal is to understand product performance, customer behavior, and pricing dynamics.
The analysis uses a dataset of over 1000 Amazon products, examining attributes like product category, pricing, discounts, and customer reviews. 
Key objectives include identifying high-revenue product categories, discount patterns, and customer engagement levels. 
The project employs Python for data cleaning, manipulation, and visualization. 
The analysis aims to provide actionable insights for optimizing sales strategies and enhancing customer satisfaction.
Insights gained from the project:
The categories that sold the greatest number of different products are: “Electronics”, “Computer & Accessories”, and “Home & Kitchen”. Each of the three categories sold 400 to 500 different products. 
The number of different products sold drops drastically for the category “Office Products” which sold 31 different products. The remaining categories only sold 1 to 2 different products.
The subcategories that sold the greatest number of different products are: “Accessories & Peripherals” and “Kitchen & Home Appliances”. The “Accessories & Peripherals” sold around 381 different products, it is also
possible that this subcategory is part of the “Computers & Accessories” category. The “Kitchen & Home Appliances” subcategory sold around 308 different products, it is also possible that this subcategory may be a
part of the “Electronics”, and “Home & Kitchen” categories.
The highest average price per products before and after discount is for the “Electronics” category. The “Home & Kitchen” category has the second highest average price per products before discount and has the third 
highest average price per products after discounts. The “Car & Motorbike” category has the third highest average price per products before discount and has the second highest average price per products after 
discount. It can also be predicted from the graph that the “Home & Kitchen” category may have higher discounts on average compared to the “Car & Motorbike” category. Even though the “Computers & Accessories” 
category has the second greatest number is selling different products, the average price per products before and after discounts are low compared to the “Electronics” and “Home & Kitchen” products. These low prices
may contribute to the large variety of different products sold in the “Computers & Accessories” category. 
The subcategories “Laptops” and “Tablets” have the highest average price per products before and after discounts. Even though the category “Computer & Accessories” has a small average price per products, 
the “Laptops” and “Tablets” subcategories have the highest average price per products. This is because both of these subcategories make up a total of 0.14% of the list of products in the data frame. 
The “Computers & Accessories” category only make up to 0.28% of the list of products even with the addition of subcategory “Monitors” that has the 4th highest average product price. The three subcategories 
“Home Theater, TV & Video”, “Mobiles & Accessories”, and “Wearable Technology” have the highest average price and these 24 subcategories belong to the category “Electronics”. 
These subcategories make up 27.47% of the list of products. The other two subcategories “Heating, Cooling & Air Quality” and “Kitchen & Home Appliances” that belong to the category “Home & Kitchen” with the
highest average price make up 28.94% of the product list.
The majority of products are rated 4 to 4.5 stars. A rating of 4.3 stars is the most common rating, followed by 4.2 and 3.9. There are few products between 2 to 3.5 stars and there are no products with less than
2 stars. In general, customers find that the products listed in the data frame are above average in quality. The customers who purchased products from the categories “Office Products” and “Toys & Games” has the 
highest customer satisfaction with ratings approximating to 4.3 stars. The difference between the highest average satisfaction rating and the lowest average satisfaction rating is 0.5 to 0.8 stars. 
There is no category that has an overall satThe subcategory “Kitchen & Dining” has the greatest number of customers rating the product. 
This category has highest average rating count with an average of 270,563. This suggests that products in this subcategory, on average, have received a significantly larger number of ratings compared to other 
subcategories. The subcategory “Accessories” has the second-highest average rating count at 84,512.6. It can be concluded that the average rating count for the 
subcategory “Kitchen & Dining” is approximately 2.86 times higher than that of subcategory “Accessories”.isfaction rating below 3.8 indicating that customers are satisfied with their purchases throughout each category. 
The customers who purchased products from the subcategory “Tablets” showed the highest overall satisfaction approximating to 4.6 stars. The difference between the highest average satisfaction rating and the 
lowest average satisfaction rating is 0.5 to 0.8 stars. There is no category that has an overall satisfaction rating below 3.8 indicating that customers are satisfied with their purchases throughout each category.
The category “Musical Instruments” has the greatest number of customers rating the product. Although this category has the highest average rating count, the category only has 2 unique products. This indicates 
that these 2 products are more popular among the other products in that category. The average rating count for the category “Toys & Games” is higher than the category “Home & Kitchen”, even though “Toys & Games”
only has 1 unique product and “Home & Kitchen” has 448 unique products. There is requirement to find why the products sold in the category “Musical Instruments” and the “Toys & Games” category are so popular.
The categories “Computers & Accessories”, “Electronics”, and “Home & Kitchen” have the greatest range of discount percentages. The category “Computers & Accessories” shows a relatively high median discount
percentage, appearing to be around 50% to 60%. The median discount percentage for the category “Electronic” is also relatively high appearing to be around 40% to 50%. Categories like “Office Products”,
“Toys & Games”, “Car & Motorbike”, generally offer much smaller discounts, suggesting different pricing strategies or potentially higher demand at their regular prices. The presence of outliers indicates that
within most categories, there are some products being offered with significantly higher discounts than the typical range for that category, possibly due to promotions.
The category “Electronics” has a relatively high median actual price appearing to be somewhere around ₹8,000 - ₹10,000. The “Electronics” category has the widest range of actual prices and includes the most 
expensive items. “Computers & Accessories” also has some higher-priced items but generally falls in a lower price range than “Electronics”. The presence of outliers in several categories indicates that within
each category, there are some products that are significantly more expensive than the majority.
