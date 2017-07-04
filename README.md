# NYC Rent Prediction Using Linear Models

Problem: A real estate agent wants to estimate the market rate for some apartments in NYC that just went into the market again. They want to use the data posted by the Census in 2014.

Approach:  Create and validate a machine learning approach to predict the monthly rent of an apartment.

Assumptions: 1) Only used features that apply to pricing an apartment that is not currently rented. 2) The market prices don't increase, so the rent for a new tenant would be the same as for the current tenant.

## Data 
The raw data can be downloaded from : https://www.census.gov/housing/nychvs/data/2014/userinfo2.html

A parsed version is uploaded to figshare: https://ndownloader.figshare.com/files/7586326

## Files
- main_rent.py includes all the codes for cleaning the data and models.
- test_score.py includes the code for testing the r^2 using various enviroments on travis
- .travis.yml and requirements-travis.txt are the necessary files for testing py file on travis website.
 
 


