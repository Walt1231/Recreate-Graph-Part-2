# Recreate-Graph-Part-2
Recreate Graph Part 2



Things we want to represent with our graphs is cumulative sum of the interest paid over 30 years:


The black line is the 30 year mortgage at 5% and the blue line is the 30 year mortgage at 3%. 
This graph is the cumulative interest paid over the course of the loan.
To accomplish this I created two filters:
First filter was for Mortgage Name is '30 Year' for an interest rate of 3% and interest rate of 5%
Then we need to use the cumsum function to get the cumulative sum paid.
The x value of my plot is the months on each of my filters and 
the y values cumulative of 5% and the cumulative of the 3% of the interest paid.
The graphs gives us a good visual cumulative interest paid over the course of the loan. 
We can see that at 3% we pay less money in interest over 30 years.

