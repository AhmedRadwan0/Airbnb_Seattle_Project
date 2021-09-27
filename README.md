# Airbnb_Seattle_Project
Analyzing and modelling data from Airbnb Seattle
### Motivation
The goal of this project is to get some insights from the dataset provided by Seattle Airbnb using the CRISP-DM process (Cross Industry Standard Process for Data Mining). 
We were mainly interseted in finding answers to the following questions:
1. What are the most and the least expensive listings in Seattle?
2. What are the most and least expensive places in Seattle?
3. How do the prices of the listings differ across the year?
4. Can we predict the price of a listing in Seattle? What are the factors that highly affect the pricing by Airbnb Seattle?

To answer the questions, the Airbnb Seattle dataset was cleaned by dropping irrelevant features and Nan data, changing from categorical values to numerical values and normalizing
the numerical features to be ready to be fed in a model based on RandomForestClassifier.

### Dependency
The code should run with no issues using Python versions 3.* with the libararies:
(Numpy, Pandas, Matplotlib, Seaborn, datetime, sklearn)

## File Structure
```
├── Data_Airbnb
│   ├── calendar.csv                    # contains information about the availability of the listings
│   ├── listings.csv                    # contains information about the listings and their related features 
│   ├── reviews.csv                     # contains information about the reviews of the listings
├── Airbnb_Seatle_Project.ipynb         # Jupyter notebook used to make the data analysis and data modelling
├── average_price_across_the_year.png   # plot for the average price of the properties across the year
├── average_price_property_types.png    # plot for the average price for each property type in Seattle
├── Lowest5_price_neighbourhood.png     # plot for the neighbourhoods in Seattle with lowest price per night for rent
├── Top5_price_neighbourhood.png        # plot for the neighbourhoods in Seattle with highest price per night for rent
├── README.md

```

## Summary of the results:
1. Boats and Condominiums are the most expensive properties in Seattle where dorms and tents are the least expensive ones
2. Fairmount Park, Industrial District and Portage Bay are the most expensive neighbourhood in Seattle to rent in where (Roxhill, Olympic Hills and Dunlap) are the cheapest.
3. Expect a higher rent prices in summer (June- July -August) and the best time to rent in Seattle would be in January and February.
4. The most important features affect the pricing by Airbnb: (number of bedrooms - cleaning fees - room type - Number of bathrooms - location - availability)


### A blog post
[Click here to see the blog post on Medium.com](https://medium.com/@ahmed.lotfy7/three-interesting-insights-from-seattle-city-airbnb-dataset-c9969c3d67f) 
