## Identifying countries in need of economic aid using Hierarchical and K-Means Clustering Algorithms

This code uses K-Means clustering to identify clusters of countries in the direst need of aid based on their economic indicators. The economic indicators used in this analysis include GDP per capita, child mortality rate, and income.


### Brief description of methodology:

1. A thorough Exploratory Data Analysis exercise is performed to tease out trends and correlations between different economic and health indicators of different countries
2. Variables are re-scaled using the Standard Scaler (remove mean and scale to unit variance)
3. Run different clustering algorithms - Hierarchical and K-Means - to identify the optimal number of clusters using elbow curves and dendrograms (ideal clusters comes out to be between 3 and 4, we picked 3)
4. Analyze characteristics of different clusters to analyze what characteristics make them distinctive


### Results:

Three natural clusters of countries were obtained using the data. The cluster corresponding to the countries in direst need of aid had the lowest income, GDP per capita, and also fared badly on health indicators such as Child Mortality rates.
