# airbnb_analysis
airbnb_analysis  NYC 2019

Airbnb is an online marketplace and hospitality services that facilitates leasing or renting of
residential properties to guests in this project I have started a series to explain exploratory data
analysis with a particular NYC 2019 datasets to help to understand the EDA.
Now I have some steps to explain the EDA in NYC Airbnb to get the intuition of approaching
EDA for any problem.
There is some problem statement of EDA in NYC Airbnb dataset through which we can easily
understand the dataset of NYC Airbnb are as follows:


1.How many columns are there in datasets?

2.what are the datatypes of those columns?

3.How many data points contains null value (i.e. missing values)?

4.What can we learn about different hosts and areas?

5.What can we learn from predictions? (ex: locations, prices, reviews, etc.)

6.Which hosts are the busiest and why?

7.Is there any noticeable difference of traffic among different areas and what could be the reason
for it?

I have followed below mentioned approaches for my first cut solution to this problem. In this
there are two approaches one is non-graphical approaches and second is graphical approaches.
1. Non-Graphical Approach:
In this Non-Graphical Approach, using functions such as shape, summary, describe, isnull,
info, datatypes and many more
 Data Cleaning: For handling data, there are many NULL values and missing
values into the data and replaced all the NaN values by the values of that features.
 Describe: using this functions, we can see the datatypes, memory usage as shown
in the outputs along with the descriptive statistics.
2. Graphical Approach:
In this Graphical Approach, using plots such as bar, scatter, histogram, box, correlations.
 Correlation Plot: To find the correlation among the variable, we can make use of
correlation functions. We can visualize the correlation matrix using seaborn
library.
