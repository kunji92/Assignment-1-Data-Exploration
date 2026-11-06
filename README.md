# Assignment-1-Data-Exploration
		
	1) Sum, Count, Average:	
		• What is the total price of all products in the dataset?
    I found total price of all products using =SUM() function 
		• How many products are there in the dataset?
    Found number of products using =COUNTA() function
		• Calculate the average price of the products.
    Calculated average price of product =AVERAGE() function
		
	2) Min and Max:	
		• Determine the minimum price among all products.
    Found the minimum price among all products using =MIN()
		• Find the maximum price among all products.
    Calculated the maximum price among all products =MAX()
		
	3) IF Function:	
		• Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.
    Found the Price Range using =IFS(D2>=500, "High Price", TRUE, "Standard Price")
    
		
	4) SUMIF and COUNTIF:	
		• Calculate the total price for products in the 'Electronics' category using the SUMIF function.
     Calculate the total price for products in the 'Electronics' using  =SUMIF(F2:F35, "Electronics", D2:D35)
		• Determine the count of products with a price less than $100 using the COUNTIF function.
     Found the count of products with a price less than $100 using =COUNTIF(D2:D35,"<100")
		
	5) Text Formatting - LEFT, RIGHT, MID:	
		• Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function.
    Created a new column named  Day using =LEFT(A2,2)
		• Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function.
    Created a new column named Country Code using =RIGHT(A2,2)
		• Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function.
    Created a new column named Month using =MID(A2,4,3)
		
		
