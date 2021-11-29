# Miami-Housing-Analysis

This is a dating and mapping analysis project using a [Miami Housing Dataset](https://www.kaggle.com/deepcontractor/miami-housing-dataset). The project mainly focuses upon numerous Miami housing attributes and how they correlate to house sales prices

## Libraries

Libraries used in this project include:
- [Pandas](https://pandas.pydata.org/)
- [Geopandas](https://geopandas.org/en/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Shapely](https://pypi.org/project/Shapely/)
- [Contextily](https://anaconda.org/conda-forge/contextily)

## Project Elements

The project includes three different sections:
### 1. Pearson Correlation
Sale Price (SALE_PRC) serves as the dependent variable, with other select columns serving as independent variables in their own respective subplots

### 2. Matrix 
The correlation matrix table in this project depicts correlation coefficient between each column in the included dataset.

# Insights 

In general, we see that there are a significant number of negative correlations in our data. Generally speaking,
that means that as the value of the observed column on the x-axis increases, sale prices (y-axis) decreases. Example: As a house's 
distance from the ocean coast increases, sale prices decrease.

Insights: The most expensive houses (and by likely extension, the houses of Miami's wealthiest individiuals) are:
1) Either close to the Miami coast or near city/commercial centres,
2) Away from highways as a means of avoiding noise pollution,
3) Either near or away from rail lines, with nearer houses perhaps looking to take advantage of rail transit,   
4) Likely to be larger houses,
5) In a house that could either be older or younger in age, with slight likelihood of being younger.
