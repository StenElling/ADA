# Title
What makes people move house in Zurich?
# Abstract
Zurich is Switzerland's biggest city and a financial hub. Hence it attracts people from all over Switzerland and the world. We want to find out, which factors have an impact on the behavior of people with respect to moving in and out of Zurich or moving around in the city. Using data provided by opendata.swiss we look for patterns and how they are related to different population groups. The results of this analysis could help with future city planning, since living space and its use are crucial topics for most big cities. 

# Research questions
1) Where do people move from/to or within the city of Zurich? 
2) Are there patterns in these movements and do the differ according to age, gender, civil status, nationality, income? 
3) Do these patterns change over the years, in particular did the financial crisis have a noticeable impact?
4) Are moving patterns correlated to the availability of local amenities like the number of schools, access to public transport, supermarkets etc? 
5) How can our results be used for city planning?


# Dataset
1) Annual population count by local district, age group and gender (300,000) 
2) Annual population count by local district and nationality (75,000) 
3) Number of people moving to a local district from outside (Swiss canton or country) with gender, age group, civil status (500,000) 
4) Number of people moving to a local district from within Zurich with gender, age group, civil status (300,000) 
5) Number of people leaving a local district to outside (Swiss canton or country) with gender, age group, civil status (500,000) 

These datasets consistently use the same identification codes and names for local areas. Moreover attributes like civil status are fully documented on the opendata pages of the City of Zurich. 
 
Data sets with monthly data for the period 2013 to 2017 exist as well. This data does not include civil status, has broader age groups and only distinguishes Swiss people from foreigners. 
 
We aim to enrich our data with (un)employment data from statistik.zh.ch . For these sets documentation exists as well. Other data used may be the median income for single people, couples and single parents in order to establish which local districts have a wealthier population and hence may be more affected by the changes due to the financial crisis.  

# A list of internal milestones up until project milestone 2
Milestone week 1 (6/11)
Aggregate the data from the website. Analyze and clean each data set. Translate data from German to English. Combine data sets were suitable into large dataframes for subsequent analysis.

Milestone week 2-3 (20/11)
Carry out time series analyses of data for different subsets of the population (e.g. grouped by age or civil status). Compare and contrast results for different subsets. Summarize some of the main results. 
Identify interesting patterns and their changes over times. Find suitable external data sets to enrich main data frame carry out more detailed analysis.

Milestone week 4 (29/11)
Look for correlations between moving patterns and local amenities (the number of schools, availability of public transport, supermarkets etc). Investigate some interesting patterns in more detail and find sutiable ways for visualising these. 

# Questions for TAs
