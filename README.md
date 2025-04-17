# Python-project_New-York-Airbnb-Data-Analysis
Analyzing Airbnb data to explore pricing trends, availability, and neighborhood insights across New York City.

# Objective
The goal of this project is to explore and analyze Airbnb listings data in New York City. The focus is on understanding pricing patterns, availability trends, neighborhood preferences, and identifying factors that influence listing prices. The project walks through:

1: Data cleaning and preprocessing

2: Univariate and bivariate analysis

3: Feature engineering

4: Visualization of relationships between key variables

# Key Insights
1: Price Distribution:

  Prices are heavily skewed to the right with many listings priced below $500, but a few outliers go above $1000.
   
  Outliers were removed for better visualization and analysis.
   
2: Neighborhood Group Analysis:

  Manhattan has the highest average price among all boroughs.
   
  Brooklyn offers more affordable options but with slightly less availability.
   
3: Room Type Trends:

  Entire homes/apartments are the most expensive and most commonly listed.
   
  Private rooms are more budget-friendly and widely available.
   
4: Availability vs Price:

  Listings with high availability do not necessarily have higher prices.
   
  Some highly available listings are still affordable, suggesting price is influenced by more than just availability.
   
5: Review and Pricing Relationship:

   Listings with more reviews tend to have moderate pricing.
   
   Very expensive listings often have fewer reviews.
   
6: Feature Engineering:

   A new feature price per bed was created to normalize price comparisons across listings.
   
7: Correlation Heatmap:
  
   Price shows weak correlation with most numeric features, suggesting other factors (like location, room type) play a more significant role.
   
   number_of_reviews and reviews_per_month are moderately correlated.

# Conclusion

1. The Airbnb market in New York is diverse, with significant variation in price and availability based on location and room type.

2. Data cleaning and outlier removal were essential to reveal true patterns in the data.

3. Manhattan leads in pricing, while Brooklyn and Queens provide budget-friendly alternatives.

4. Insights gained from this analysis can help both hosts optimize their listings and travelers make more informed decisions.
