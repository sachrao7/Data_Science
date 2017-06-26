
Problem want to solve:

Given a list of health, education, and income indicators, be able to predict overall life expectancy for a given country. 

Why: 
Client could be considered for any organizations, nonprofits, policymakers in order to provide an engine that allows us to input a certain country’s education, level, income, disease outbreak percentage, quality of energy resources, unemployment rate, and total health spending and output an expected life expectancy percentage. 

Data:
Will use data on gapminder- which gives a list of 166 different indicators on a global level that aggregates sources from various data providers. Some of these data providers include The world bank, international labour organization, WHO, and world health organization. Much of this data is available for an excel/csv download, however would be a good data ingestion exercise  if I’m able to parse through the site and grab the cvs downloads. Potential problems of this dataset is that there is not many entries. Suppoeably on average 150 countries that have some sort of substantial data over 20 years (3000). However this task would provide a good opportunity to explore a multitude of features through EDA, data visualizations with different variables, and a simple prediction engine. 

Outline of approach:
Gather all list of features (each csv is one feature) and join data together on country. Each country would have about 20 data points for the 20 years. And given about 150 countries, this would lead to 3 thousand data points. Split the dataset into training and testing set and cross validate the data. The model would be a multi-variable linear regression. 

Deliverables:
This would include an overview of the project, documented code in the form of ipython notebooks, and links to original data sources
