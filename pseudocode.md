Steps to finding solution for Console Finances:

1) Count the number of items in the array;
2) Store the above value as months
3) Sum the amounts in position 1 of each array element;
4) Store the above value as Total;
5) Add a third element to each array, [month, amount, diff];
6) Calculate the difference between amount for each month until all months are calculated;  
7) Perform calculation on the new element (difference) as follows: Sum(difference) / NumberOfMonths
8) Store the above value as AveragePL;
9) Sort the finances var by new column, difference;
10) Access the first and last rows for the greatest increase and decrease in profit;
11) Build text for return to console:

"Financial Analysis" +
"----------------------------" +
Total Months: " + months +
"Total: $" + total +
"Average Change: $" + AveragePL +
"Greatest Increase in Profits: " + LargestPLMonth + "($" + LargestPL +")" +
"Greatest Decrease in Profits: " + SmallestPLMonth + "($" + SmallestPL +")" +