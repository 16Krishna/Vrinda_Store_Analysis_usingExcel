# Vrinda_Store_Analysis_usingExcel_&_PowerBI
Analysis of Vrinda Store Data to improve more Sales in 2023


# Vrinda Store Analysis


## Objective:

Vrinda Store wants to create an Annual Sales Report for 2022. So, that Vrinda can understand their customers and grow sales in 2023

## Sample Questions:

1. Compare the sales and order using single chart
2. Which month got the highest sales and orders?
3. Who purchased more – Men or Women?
4. What are the different orders status in 2022?
5. List the top 10 states contributing to the sales
6. Relation between age and gender based on number of orders
7. Which channel is contributing to maximum sales?
8. Highest Selling category?



### Steps followed 

- Step 1 : Data cleaning:
		In the gender column, all the 'M' was given as Male and 'F' was Female
		The Qty column, all the One was replaced with 1 and all the Two was replaced by 2

- Step 2 : Data Processing/DAX:
		Extraction of Month from each cell using =TEXT(A1, "mmmm")
		Created Age Group column such that the relation between age and gender can be found out
			=IFS(E2>60,"Senior",E2>20,"Adult",E2>0,"Teens")

Now we will analyze the data-

- Step 3 : 
	Graph - 1: Sales vs Orders: Which month gives maximum sales?

- Step 4 : 
	Graph - 2: Men vs Women: To know who does more shopping

- Step 5 : 
	Graph - 3: Top 5 state orders in 2022

- Step 6 : 
	Graph - 4: How many orders remain cancelled, delivered, refunded and returned?

- Step 7 : 
	Graph - 5: Which age group does more shopping? Are they from adults, seniors or teens?

- Step 8 : 
	Graph - 6: Which channel contributes more to sales?



## Insights/Conclusion:

1. Women are more likely to buy products than men (~64%)
2. Maximum Adult women within the age group (20-60 years) buyers contribute to the sales
3. Max sales happens in March, followed by August
4. Bengaluru, Hyderabad, and Delhi are the top three cities with max buyers
5. Amazon, Myntra, and Flipkart are the channels with the maximum number of buyers



