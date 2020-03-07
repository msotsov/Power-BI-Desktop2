# Power-BI-Desktop2

My another project using Power BI Desktop. The purpose of this project is to find the value in Euro of different currency amounts using the currency rates data from web source.

<i>Data source: https://www.eestipank.ee/en/exchange-rates

Used tables from data source: Table 0, Table 1

Used data from tables: Both tables contains currency rates (from Euro)

Another used tables: Currency position (with own data)

Visuals: Both visuals represents the same results but in different views</i>

<b>Project steps</b>

Step 1: 
Taking the data from web source (currency rates)

Step 2:
Edit tables (add column headers)

Step 3: 
Combine queries (create new table called 'Currency rates' from Table 0 and Table 1)

Step 4:
Apply changes

Step 5:
Create table called 'Currency position' and enter the data with specific currency position:

USD 100.000
SEK 1.000.000
CZK 5.000.000
AUD 135.000

Step 6:
Add new column (currency abbreviation) into 'Currency rates' table in order to create the relations with 'Currency position' table. The initial 'Currency rates' table has both currency abbreviation and full name values in the name column.

Step 7:
Create relations

Step 8: 
Add new column (value in Euro) into 'Currency position' table and calculate the amount of each currency position in Euros.

Step 9:
Refresh and save

Step 10: 
Add visuals
