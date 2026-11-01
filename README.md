# Assignment1--Data-Exploration
	1) Sum, Count, Average:	
		• What is the total price of all products in the dataset? Adds all product price =SUM(D2:D35)
		• How many products are there in the dataset? Count products names (non-empty cells) =COUNT(B2:B35)
		• Calculate the average price of the products. Calculate the average product price =AVERAGE(D2:D35)
	2) Min and Max:	
		• Determine the minimum price among all products. Returns the lowest price =MIN(D2:D35)
		• Find the maximum price among all products. Returns the highest price =MAX(D2:D35)
  3) IF Function:	
	  • Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as '         Standard Price'.  Created a new column (G) for Price Range. Products priced at $500 or more named as High Price and other as Standard Price.
      =IF(D2>=500,"High Price","Standard Price")
  4) SUMIF and COUNTIF:	
		• Calculate the total price for products in the 'Electronics' category using the SUMIF function. Adds prices only where the category name is Electronics
     =SUMIF(F2:F35,"Electronics",D2:D35)
		• Determine the count of products with a price less than $100 using the COUNTIF function. Counts prices that are priced below $100.
    =COUNTIF(D2:D35,"<100")
  5) Text Formatting - LEFT, RIGHT, MID:	
		• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function. Created new column(H) named as Day for first two characters of each product =LEFT(A2:A35,2)
		• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.  Created new column(I) named as Country Code for last two characters of each product =RIGHT(A2:A35,2)
		• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function. Created new column(J) named as Month for finding three characters starting at position 4 =MID(A2:A35,4,3)




