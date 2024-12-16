

#PRE-PROCESSING STEPS

1-Removed Null Rows in Table-People

2-Made the top-row of the table People as headers.

3-Made top-row of table Returns as headers.

4-Removed Duplicates in the Order table

5-Changed type of column order date from long-date to short-date.

6-Created relationship of one to many between People & Orders 

7-Created relationship of many to many between returns & orders.

8-Created new column “updated postal code” using coalesce function to fit set the null values as 0.

9-Created new column total income using measure quantity*sales.

10- Created a group by in Orders table using Ship Mode to count number of Users under each Ship Mode & saved details in a new table.

11-Created a group by in Orders table using Segments column to get the total Sales under each Segment.

12-Created a calculated Table including Discount price calculated using Discount% & Price, also created a column to check if the sales is profit or negative using if as some values in the profit column of orders table has negative values.
