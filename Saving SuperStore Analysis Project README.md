# Saving SuperStore Analysis
![image](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/47655fae-8cc6-4117-9a64-4c13666d03f8)




## Overview
* The project task was to review the superstore's operations and increase its profitability to avoid bankruptcy.
# Saving Super Store

In this project I was hired as a consultant to review the superstore's operations and increase its profitability to avoid
bankruptcy.

Part 1: Profits & losses
Identify the important centers of profit and loss for the superstore.

Among the pairs of dimensions (e.g., subcategory + region, or shipping mode + product ID) which are the two biggest profit centers and two biggest loss-makers? Justify your conclusion with a visualization. According to the visualization, the biggest two profit centers for subcategories are (Copiers,  & Phones). The stacked bar display illustrates that these two have the most profit. To be certain I took a further step and calculated the differences between the profit and loss. Copiers did not have any profit loss. With phones I subtracted the profit of $67,000 minus the loss of $11,000 to see a better understanding of how profitable that area was. And to coincide with these findings the two biggest loss-makers are (binders and tables). Here I also took a closer step and calculated the difference which ultimately ended up with a huge profit loss for binders and a negative loss for tables. These were my findings for the biggest loss-makers


Which products should the superstore stop selling? Based on the information displayed In the second profit and losses sheet which focuses on product name and profit, the superstore should stop selling items that are in the negative for loss of profit. In the stacked bars display, please view the items that sold for a loss, they are all displayed in the color red and below zero. These should not be sold any longer by the superstore. There are profitable items and items that are taking away from overall profitability. And the items that are not producing profit should be discontinued and no longer sold. Justify your conclusion with a visualization.

Which product subcategories should the store focus on and which should they stop selling? Choose 3 of each. The subcategories that should be focused on are the accessories which had an overall profit of $50,000. The next focal point should be the appliances because this area saw a profit of $31,000. The third area that was a highlight for continued selling is the copiers subcategory due to seeing an overall profit in that area of $76,000. 

The recommendations for the three subcategories that should no longer be sold are below. The superstore should stop selling tables because they saw an overall loss of -$23,000. The next recommendation would be to stop selling bookcases due to them losing -$3,000 in profit. The last area that should no longer be sold is the supplies subcategory, it saw a loss of -$1,000.


Part 2: Advertising
The superstore wants to know if advertising would be worth it. Advertising works over time and geography, and your average profit per unit sold should be high enough to justify it.

Identify the 3 best combinations of states and month of the year to advertise in. Make a visualization of the average profit for each month of the year for those 3 states and argue how much you would be willing to pay in advertising for those states in those months.
You should be most willing to pay for advertisements based on the return on ad spend ratio. Let's say you should be willing to spend 1/5 of the profits on advertising for this exercise.

The best three combinations of states and months of the year to advertise are Alabama and Arizona. Arkansas, during August, September, and December. To better display the top three combinations index was used to get a better picture as to why these are the top three areas.


Part 3: Returned items
In the last part, we’ll use the Returns table to see if some products have abnormal rates of being returned to the store.

I LEFT JOIN’ed onto the Orders table. You should see both “Yes” and “null” values in the Returned column. This will show that the join was successful.

![image](https://github.com/Mr-DinoBlack/Data_projects_TripleTen/assets/164646396/9a335478-6bf8-4c69-9c55-1471a71b27d4)


I made the Returned field into a calculated field where the null values are 0 and the Yes values are 1.
Use this new field to make a visualization for each of the following questions: 1. Which products have the highest return rate? 2. Which customers have the highest return rate?
In a separate sheet, make a visualization of the average profit against the average return rate on a dimension of your choice (state, shipping mode, product type, etc.). Present a visual argument as to why the superstore should do away with or keep doing business on the basis of this dimension.

The products that have the highest return rates are shown using the index, and the calculation shows the average return indication displaying percentages. Numbers one through five have the highest returns and these are Acco Glide Clips, Avery 500, Bush Saratoga Collection 5-Shelf, Canon Color ImageClass, Cisco SPA 501G IP Phone.

The final display is a heat map displaying the average profit against the average return using the State as the dimension. Each square has 3 different pieces of information which include, State, size, and color. Every square is a separate State. The color schema shows the average return indication for each state, the lighter a color is the lower the return indication for the State, and the darker the color the higher the return indication is for the State. The size of the squares is related to the average profit, the larger a square is the more profitable that particular state is, and the smaller the square shows lower and in some cases a negative profit.


## Link To Project

[View my Tableau Public workbook]
(https://public.tableau.com/views/Project-SavingSuperStore/ProfitsLosses-SubcategoryCategoryRegion?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)aring

### Demo Video of Project 
* [https://www.loom.com/share/d88021f5559c453fb8f9c8d1c86ff955](https://www.loom.com/share/d954c3c51c73480ba072dce63bf795b9)

* The link above allows the users to navigate the project.



### Technologies
* To build this project, I used Tableau Public. 
