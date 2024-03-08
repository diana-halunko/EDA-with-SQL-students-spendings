# Exploratory Data Analysis with SQL
Why explore data?
help understand the quality of data
identify missing values
look for unusual or unexpected values
look for inconsistent data, especially with regard to business rules
check distribution of data, its shape
understand subgroups using histograms
check correlations between variables,using the Pearson Correlation Coefficient

Exploring data with statistics
Central Tendency (Mean, Mode)
Spread (Bell curve, long tail curve, etc) or Variance, Std Dev

Testing hypothesis with statistics
Example: customers over the age of 40 make more purchase than customers over age of 30
SELECT Avg(number_purchase), Avg(amount_purchase) FROM customer_summary WHERE age > 40
