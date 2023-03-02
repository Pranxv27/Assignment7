# Assignment7
The goal for this project was to extract on the top 100 ranked companies by forbes data from https://eqvista.com/fortune-500-companies-in-the-us/ and perform the ETL(Extract, Tranform, Load) process on it. After cleaning and converting the data I would use the newly created DataFrame and CSV file to conduct some further analysis and perform some data visulaizations.

The different attributes and their data types are described below:
Rank: int
Title= str
Montly_revenue= int
Market_value= int

There doesn't appear to be any known biases, except in the market value. Companies that are not publicly owned have a market value of 0, which doesn't exactly depict the value of the company. There minor quircks in the data. The transormation of the data was tedious, as some companies' data was extracted in a different structure compared to the rest. The resulting graphs show that rank and montly reveue have a negative correlation. Also, from the Box-plot we can see that there are quite a few outliers on the upper end, which shows that the higher raked greatly out earn the rest of the table
