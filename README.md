# house-prices-kaggle

This is a kaggle competetion to predict sales prices and practice feature engineering. It was a very helpful experience to apply what I have learned to real data in a project.

## Description
This was the description on [kaggle.com](https://www.kaggle.com):
>Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
>With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.
>

## Approach
1. Read in data with Pandas and get a first overview with info() and describe() methods
2. Creating a histogram with the Seaborn distplot function
3. Having a look on the Pandas correlation matrix with the Seaborn heatmap function
4. Using the Seaborn pairplot function, I got an overview of the most important correlations
5. Looking for NULL values with the Pandas isnull() method
6. Having a look on the skews with Pandas skew()
7. Getting dummies and training the model with a Random Forest classifier

## Difficulties
The biggest challenge was definitely the feature engineering:
- Searching the data frame for NULL values and then fixing or ignoring them
- Determining the skewness of the non-objects and fixing that too

## Conclusion
Although the project was challenging, I enjoyed it very much.  For my very first competition, I am very happy with the result. With the first submission of the estimated house prices, I achieved a placement in the top 56%.
