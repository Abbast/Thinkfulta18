# Thinkfulta18

## Background ##
This is the first capstone project within the curriculum of Thinkful's Data Science Flex Program, focusing on performing statistical analyses on a chosen dataset.   

## The Data ##
The data used for the project was obtained from the Worldwide Bureaucracy Indicators database, via the World Bank: 

https://datacatalog.worldbank.org/dataset/worldwide-bureaucracy-indicators

The data was contains census-based data on public and private sector employment in more than 130 nations between the years of 2000 to 2018. 

## Methodology ## 
Libraries used:
- Pandas
- NumPy
- Scipy
- Matplotlib
- Seaborn 

We utilized Pandas for more efficient dataframe management and manipulation. The Scipy library contains statistical packages relevant for performing formal statistical tests, including the following: Shapiro-Wilks, Normaltest, independent samples t-test, and the Kruskal-Wallis. The first two tests were used in formal tests for whether a particular variable is normally distributed or not. The latter two tests were used for A/B hypothesis testing, the first of which applied for normally distributed variables while Kruskal-Wallis is applied in the case of non-normally distributed variables.

## Future Goals ##
- Examine other socioecomomic features for possible statistical significance
- Attempt to locate missing data 
- Perform a similar analysis for US state data, if available
