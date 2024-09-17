# Airbnb_Project  


## Overview  
This project analyzes Airbnb listings from several major U.S. cities, including New York City, California, Dallas, Washington DC, and Hawaii. The analysis focuses on a variety of factors such as room types, ratings, prices, and guest accommodations. Additionally, it incorporates sentiment analysis of user reviews to extract insights regarding user experience across different Airbnb properties. This project also outlines potential extensions with machine learning techniques for predictive analysis and classification.

## Key Features  

### Data Preprocessing
- The dataset consists of Airbnb listings from NYC, California, Dallas, DC, and Hawaii.
- Each dataset is cleaned and merged into a single dataset for analysis.
- Missing values are handled, and data is filtered for distinct room types and destinations.

### Data Visualizations
- Visualizations include box plots of Airbnb ratings and prices by destination and room type.
- Distribution of room types across the various destinations is presented with both bar charts and pie charts.
- Sentiment analysis of user reviews is performed and visualized using word clouds and bar charts.

### Sentiment Analysis
- User reviews are tokenized, cleaned, and processed to identify positive and negative sentiments.
- The project utilizes the Bing sentiment lexicon to score and visualize user reviews for each destination.

### Map Visualization
- An interactive map is created using `mapboxer` that visualizes Airbnb properties, color-coded by price.
- The map includes data from NYC, California, DC, Dallas, and Hawaii, with popups showing price information for each property.

### Regression Analysis
- Linear regression models are created to analyze the impact of several variables (room type, stars, number of guests, host experience) on the price of Airbnb listings.
- The slope of different variables by destination and room type is analyzed and visualized to understand the relationship between these factors and price.

### Price Prediction Using Machine Learning Models
- Implement machine learning models like Decision Trees, Random Forest, and Gradient Boosting to predict Airbnb listing prices based on variables such as room type, guest capacity, and ratings.
  
### Sentiment Classification Using NLP
- Build classification models like Logistic Regression, Support Vector Machines (SVM), or Naive Bayes to classify Airbnb reviews as positive or negative based on text analysis.

### Clustering Listings Using K-Means or DBSCAN
- Perform clustering on Airbnb listings to group similar properties based on price, number of guests, and other factors using K-Means or DBSCAN clustering techniques.

### Recommendation System for Airbnb Listings
- Develop a recommendation system that suggests Airbnb properties to users based on their previous preferences or highly rated listings using collaborative filtering or content-based filtering methods.
