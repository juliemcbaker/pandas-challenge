# pandas-challenge
Repository for pandas homework assignment
Julie Baker
Heroes of Pymoli assignment
June 2021

Both HeroesOfPymoli_baker.ipynb and main_pymoli.ipynb contain the same code that I wrote. (I did not want to accidentally delete anything.)

The code reads in purchase_data.csv from the Resources folder.

Analysis starts with very basic breakdown of unique user count, overall total purchases and average per person.

Next, gender trends are investigated using the .groupby method, finding the number of members of each gender category as well as the percentage of players each group contains. Purchasing patterns are explored for each group.

Different age groups are then created within the dataframe using bins and pd.cut function to explore purchasing differences for different aged players. 

Next, the top 5 spenders in the game are identified.

Finally, items are analyzed to find the 5 most popular items and the 5 most profitable items.

Some key insights about the results can be found as baker_pymoli_analysis.md in the Output folder.
