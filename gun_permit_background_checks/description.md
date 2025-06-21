The very first (and most cluttered) data analysis project I did. Didn't really do any proper machine learning, but I did do a ton of data cleaning and manipulation using Pandas and data visualization with Matplotlib.

Steps I took:
1. Load a public dataset of NICS firearm background checks by state and clean it somewhat by dropping all rows with null values.
2. Analyze correlations within this dataset and graph a scatterplot with line of best fit correlating the number of long gun background checks with the number of handgun background checks.
3. Specifically look at Alabama's correlations and graph one of them.
4. Load in a dataset of recent election results in percent format to see if there would be any correlation between that percentage and the number of background checks.
5. Clean this dataset, taking only the rows and columns I need.
6. Find out that there wasn't any meaningful correlation between political party voter percentages and the number of gun background checks.
7. Load in another dataset with an actual count of voters per state for each party, rather than a percentage.
8. Graph the number of background checks with respect to the number of Republican voters. Repeat for Democrat voters.
9. Find that there's a positive correlation between the number of voters and the number of gun background checks (more people means more people with guns and more people getting background checked).
