# Statistical-Analysis
These codes were created to determine if there were statistical significance between parameters calulated
using the RAP and RUC soundings. 

The 'Normal Distribution' code was used to identify if the data was noramlly distributed and this then 
led to determine which two sample test should be used to compare the data. 

The 'Two Sample Test' code gathered all the data and compared parameters between crossing and non-crossing 
supercells. The mean, delta change, and percent change was calulated. Then the two distributions were 
compared using the two sample KS test and two sample T test. 

The 'Cross Compare' code is similar to the 'Two Sample Test' code, except it compares two different 
subcategories (i.e., April supercells vs May supercells) and does not compare between crossing and 
non-crossing supercells. 

Lastly, the 'Violin Plots' code reads in the data and creates violin plots for the statistically significant 
parameters. The data is plotted in the same order that the dataframes are in. 
