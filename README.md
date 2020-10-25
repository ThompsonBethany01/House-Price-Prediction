# Predicting Home Prices in India
## About the Project
### Goals
### Background
### Outline
### Data Dictionary
The data dictionary after the prepare stage is below.
## Initial Thoughts & Hypothesis
### Thoughts
With only 11 columns, we may need to create new features to improve the modeling process. Dummy variables, clusters, and calculated fields can be added. Plotting homes by longititude and latitude could give insight into location vs. pricing.
### Hypothesis
Certain location clusters have an effect on house prices.
> Null hypothesis: Location clusters do not have a significant difference in prices.  
> Alternative Hypothesis: At least 2 location clusters have a significant difference in pricing.  

Houses posted by a Dealer have higher or lower prices.
> Null hypothesis: Dealer or Owners posting do not effect the price of the house.  
> Alternative Hypothesis: Houses posted by Dealers have significantly higher or lower prices.  

The higher the house square feet, the higher the price.
> Null hypothesis: Square footage does not effect the price of the house.  
> Alternative Hypothesis: Houses with higher square footage have significantly higher prices.

## Project Steps
### Acquire
Data is downloaded in a zip file which contains
- train.csv
    - 29,451 rows and 12 columns
- test.csv
    - 68,720 rows and 11 columns
- sample_submission.csv
    - a sample of how the final model predictions should be stored
    - one column holding the predicted price for each house in the test.csv
### Prepare
While the data seems squeky clean, some prep that is needed includes:
- rename columns from all caps
- create dummy variables
- create clusters for location and address  
Any prep on the data will be added as a function in the Prepare.py module for reproducibility.
Note: No nulls are present in the data
### Explore

### Model
### Conclusions
## How to Reproduce
## Author
## Acknowledgments
Kaggle Competition Link Provided [Here](https://www.kaggle.com/anmolkumar/house-price-prediction-challenge?select=train.csv)