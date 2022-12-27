Steps to finding solution for Console Finances:

1) Count the number of items in the array;
2) Store the above value as NumberOfMonths
3) Sum the amounts in position 1 of each array element;
4) Store the above value as Total;
5) Add a third element to each array, [month, amount, difference];
6) Calculate the difference between amount for each month until all months are calculated;  
7) Perform calculation on the new element (difference) as follows: Sum(difference) / NumberOfMonths
8) Store the above value as AveragePL;
9) Return the largest value in the element difference;
10) Store the above value as LargestPL;
11) Return the smallest value in the element difference;
12) Store the above value as SmallestPL;
13) Reverse lookup to find values of month for each of LargestPL and SmallestPL;
13) Build text for return to console:

"Financial Analysis" &&
"----------------------------" &&
Total Months: " && NumberOfMonths &&
"Total: $" && Total &&
"Average Change: $" &&AveragePL &&
"Greatest Increase in Profits: " && LargestPLMonth && "($" && LargestPL &&")" &&
"Greatest Decrease in Profits: " && SmallestPLMonth && "($" && SmallestPL &&")" &&