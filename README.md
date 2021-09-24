# Inside Airbnb London (UK) Data Analysis

Analysing Airbnb's London market, using linear and quantile regression in Python

## Summary

Inside Airbnb is an independent, non-commercial set of tools and data that allows us to explore how Airbnb (a short-term accommodation marketplace connecting tourists and tenants with residential home owners) is really being used in cities around the world.

In this project, I analysed data on London in an attempt to discover:

1. How do the different neighborhoods typically compare in price?
2. How do the different neighborhoods typically compare in number of reviews per month?
3. What else is typically important for getting more reviews per month (i.e. the top 5 influential features)?

To answer these questions I fitted one regression model to describe the relationship between a selection of listings' features and the price, and one to describe the relationship between listings' features and the rate of reviews posted (which serves as a proxy for the number of bookings, in the absence of this information).

Given the effect that the coronavirus pandemic has had on travel and hospitality in 2020, I only analysed pre-2020 data.

An accompanying blog post can be found [here](https://joelalgee.medium.com/inside-airbnb-london-uk-data-analysis-4628b4915e7e).

## Package versions

* python 3.8.5
* numpy 1.20.1
* pandas 1.2.4
* matplotlib 3.3.4
* statsmodels	0.12.2

## Instructions

1. Extract listings.csv from listings.zip and save  in same folder as airbnb_london.ipynb
2. Use Jupyter Notebook to open airbnb_london.ipynb

Alternatively, open airbnb_london.html for a non-interactive version of the analysis and discussion.

## Files

### 1. airbnb_london.ipynb:

Contains the step-by-step analysis and discussion as an interactive Jupyter Notebook.

### 2. airbnb_london.html:

Static HTML version of the above

### 3. listings.zip

The zipped data used for the analysis.

## Credits

* Airbnb data is provided by [Inside Airbnb](http://insideairbnb.com/get-the-data.html).
