# SEATTLE-AirBnB

The earning that can to get for place in this platform, it is influenced to the day that this place has been occupied. For this reason is important to know which features affect or improve the occupation percentage. This Notebook look up analyzes which are features to influence in the occupation of a place in Seattle and answer three question of interest :

There are three questions of interest :

1.How the features of places influence in its occupation?

2.How is the occupation this places in analyzed time?

3.How are the place with more prices ? Is high their occupation ?

# Libraries used

- numpy.
- pandas.
- os.
- seaborn.
- matplotlib.pyplot.
- decimal.
- sklearn.

# Dataset

1. listings.csv : This dataset show information of  features the places of Seattle such as price, bedrooms, location, property type etc.
2. calendar.csv: This dataset show information of  availability dates, price for each date and place.

# Results of the analysis

This analysis look up to know which features have influence in the occupation of a place in Seattle. In a general analysis grouped dates of datasets to calculate the occupation percentage during all year, and builed a correlation matrix where there were not features with strong coefficients with the occupation.

In an occupation analysis by month, weekday and several features of interest. This shows that for the main property type, Apartment and House, there are two season with more occupation but this percentage never to get more that 50%. By room type “Entire” is most frequent and its percentage is more high in January. The neighborhoods that have a better performance in the occupation percentage are Capitol Hill, Downtown and Queen Anne. Other analysis was if the price influences in the occupation percentage. There is not difference between expensive places and cheaper places.
