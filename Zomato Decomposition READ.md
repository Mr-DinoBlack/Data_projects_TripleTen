# Zomato Analysis

![Report](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/e1d9c97d-1123-48a9-abf9-3e25de51ff41)


## Overview

![Fork   Spoon](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/2257cdbe-0af5-4790-8290-9ac03b846bab)


Brief overview of the purpose of the report and the significance of the data analysis.
Zomato is a multinational restaurant aggregator and food delivery company.
The purpose of the Zomato KPI dashboard was to share key business metrics from Zomato. The dashboard will give better insight and clarity of sales & revenue over time, cuisine performance, cities, and customers. 

## Hypothesis

![Questions](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/ee95b700-e4c2-447b-b12f-c9ff34f91888)


The dynamics of sales/revenue over time for the Zomato restaurant group will reveal seasonal trends and patterns, with peak sales occurring during certain months or periods. Main KPIs such as total sales, total revenue, and total number of customers will exhibit fluctuations corresponding to consumer preferences and economic factors. Additionally, there may be a shift in the distribution of sales across different locations or restaurant concepts within the group, indicating changes in market demand or strategic shifts in business focus.

## Mockup of Dashboard

![IMG_2947](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/558e91ea-929c-4231-bcbf-256f6721d453)


## Key 🔑 findings and insights derived from the Tableau dashboard

![BANS](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/fb2821e6-d978-43b6-9190-235090ebfc7f)

## Sales by Month 

![Sales by Year   Month](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/62641550-d717-4e98-9432-3feee32c6703)

The first chart that I built was Sales by Year & Month. Line charts and graphs are useful when measuring time. I constructed a combo line graph adding circles to easier track the months and how the restaurant group did as a whole over the course of time. The graph shows all the months of the year, while hovering over a circle users can see the sales amount and the sales quantity. To show the performance of different years, I added a filter for users to be able to do so. Based on the findings for 2017, the only months that did business were October, November, and December. Which could be the business launching, and doing soft openings to test the markets and cities of India. In 2018, there was significant growth which can be seen by the months of the year that did business, the sales amount, and the sales quantity. 2019 was a profitable year. There was a drop in the total sales amount, sales quantity, and number of customers. In 2020 there was a bigger decline in sales amount (revenue), and total sales (quantity),  and customers. The recommendation here would be to focus on bringing in the strategy from 2018. This was the best year the business experienced, sales amount, sales quantity, and number of customers were the highest compared to other years. For the strategy in which the customers were targeted, it would be important to try to replicate that by engaging with those customer accounts, and even possibly expanding more of the popular cuisines to more places since they accounted for a higher amount of sales quantity, and sales amount for revenue.

## Sales by Cuisines

![Sales by Cuisine](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/652ff324-d7a5-4c72-ae6f-94abddd71c48)

The second chart I built was a bar graph of Sales by Cusines. The filter I chose to add here was one for years. It allows users to be able to see what the top cuisines were for 2017-2020. A key finding I identified right away was that when looking at all of the combined years together, not all cuisines even did business, and many cuisines showed a small amount of sales quantity, and sales revenue. For each year, the top 20-25 cuisines stayed consistent. There were shifts in sales amount (revenue) and sales quantity, the top 20-25 stayed relatively the same. This matters because it will identify which cuisines are the most popular, and where Zomato resources should be focused. The recommendation here is to consider discontinuing cuisines that are not popular. Or cuisines that account for a smaller amount or no sales revenue, or lower sales quantity and replace them with popular cuisines with higher sales figures, and sales quantities. 

## Sales by City

![Sales by City](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/9c56a345-68bd-4aea-8401-984b248fb565)

The third chart I built was Sales by City. This Map shows all of the cities in India where transactions have happened. I added a parameter entitled ‘Choose A Metric’ that shows Sales Amount as Revenue, and Sales Quantity as Sales Quantity. Then I created a calculated field entitled ‘Metric Selected’, the calculation here is CASE [Choose A Metric] WHEN ‘Sales Amount’ THEN [Sales Amount] WHEN ‘Sales Quantity’ THEN [Sales Quantity] END. Multiple filters on this page help show different insights. ‘Choose A Metric’ helps to show the revenue or sales quantity for city or cities. Users can click on either one, and then hover over the city to see more information. On the map, users can see circles of different sizes. The bigger a circle corresponds to the total revenue or sales quantity. The trend over time here shows that every year, there were new customers and transactions in new areas. The recommendation here is to find a way to continue to engage with customers consistently so that customer retention can stay higher over time. This is important because more new circles can be seen each year, and the goal should be to work towards keeping new customers who have done business with Zomato.

## Sales by User ID

![Sales by User ID](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/e065a55f-dc57-459f-a81b-82f2318fc11a)

The Sales by User ID bar graph chart I constructed using User ID measures the purchases of users by the year. This was the fourth chart I built. The bars on the graph show the User ID, total sales amount, and the sales quantity when a user hovers over it. This is helpful because users can see what customers did the most business that year. As a business, this is an important metric because it can be a strong indicator of who certain loyal customers are, can be, or should be. It also shows who can be engaged with more. The recommendation here is to better understand who the customers are. An important thought to consider is what differences there are between the customers with the highest sales amount and sales quantities.Versus the customers that are seen with a lower number. Customer engagement and retention should be the core focus here once again, and adding details to their profile. Details can be specials catered towards their favorite food, family size, delivery coupons if they like to do take out rather than dining in, happy hour promotions, or dinner specials for those that prefer to dine in.

## Summary of The Main Findings & Recommendations

![Zomato Dashboard](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/4467c0d0-3932-4b1c-bbdd-7fed6176238b)


Sales by Year & Month. 
The recommendation for Sales by Year & Month would be to focus on bringing in the strategy from 2018. This was the best year the business experienced. Sales amount, sales quantity, and number of customers were the highest compared to other years. However the customers were targeted, it would be important to try to replicate that by engaging with those customer accounts, and expanding more of the popular cuisines to more places since they account for higher sales quantities and revenue.
Sales by Cusines. 
The recommendation for Sales by Cuisines is to discontinue cuisines that are not popular or account for a small amount of sales revenue or sales quantity. And replace them with the popular cuisines that account for higher revenue, and sales quantities. 
Sales by City. 
The recommendation for Sales by City is to find a way to continue to engage with customers consistently so that customer retention can stay higher over time. This is important because more new circles can be seen each year, and the goal should be to work towards keeping them.
Sales by User ID 
The recommendation for Sales by User is to gather more information on who the customers are. Find out the differences between the customers with the highest sales revenue, and sales quantities, versus the customers that show a trend of similar spent revenue and sales quantities. Customer engagement and retention should be the core focus here once again, and adding details to their profile. Details can be specials catered towards their favorite food, family size, delivery coupons if they like to do take out rather than dining in, happy hour promotions or dinner specials for those that prefer to dine in.





# Tools I Used & Links I Created Below

## Tableau, Google Docs, Loom
I used Tableau to complete my final project. I used Google Docs to create a comprehensive write up. I hand drew my dashboard mockups, and I used loom to
creat a screencast walking users through my project and how to navigate it.


https://public.tableau.com/views/Zomato-FinalProject/ZomatoKPIDashboard?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link

https://www.loom.com/share/91e19bdf60bd48778ca8603baad97c5e?sid=472e183a-d168-4da9-abba-0571cb28672b

https://www.loom.com/share/5f56219eb0c74e0f9772908887100986?sid=541ad2d7-2d80-42bc-9238-3adee366047b

https://www.loom.com/share/8c94d856e2ad43e385883b737b95db16?sid=889b9213-9d0c-4425-bd08-585ba14ab879
