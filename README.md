# Housing Price Prediction Model

## Respository Contents
***reorder this later at final stage***
* `README.md`: public-facing text file that's previewed on github repository
* `draft_process.ipynb`: scrap Jupyter notebook used to experiment with modeling process, using training data from `kc_house_data_train.csv`
	* ***this may be moved to a folder later***
* `final_modeling_process.ipynb`: final Jupyter notebook with 'cleaned up' modeling process
* `predict_holdout.ipynb`: Jupyter notebook used to generate predictions using final model on testing data from `kc_house_data_houldout_features.csv`
* `kc_house_data_train.csv`: CSV file with **training data**, pre-split from dataset of King County housing information
* `kc_house_data_houldout_features.csv`: CSV file with **testing data**, pre-split from dataset of King County housing information
* `housing_preds_sidney_kung`: final CSV file of housing price predictions on testing/holdout set
* `images`: folder with visualizations used in README.md

## Overview

This project builds a model to predict how much someone will pay for a house in King County Seatle, Washington. Inital exploratory data analysis shows that [something]. Based on that discovery, the model used [these initial features] to determine house prices based on unseen data. After [number] iterations, the final model has an R-Squared of [number] and RMSE of [number]. The final model's predictions on the holdout set can be found in [housing_preds_sidney_kung.csv]

## Data & Methods

This model has been developed by using the traing set, `kc_house_data_train.csv`. It was then predicted on the `kc_house_data_holdout_features.csv`. The resulting dataframe has been saved as `housing_preds_sidney_kung.csv`.

The overall data set contains information about houses that were sold in King County in Seattle, Washington during the last decade. Below is a description of the column names, to help gain a better understanding about what the data represents. 

| column name | description |
|-|-|
| **id** | unique ID for each home |
| **date** | date the home was sold |
| **price** | selling price of each home |
| **bedrooms** | number of bedrooms |
| **bathrooms** | number of bathrooms, where .5 accounts for a room with a toilet but no shower |
| **sqft_living** | square footage of each home's interior living space |
| **sqft_lot** | square footage of each home's land space |
| **floors** | number of floors (levels) in house |
| **waterfront** | dummy varibale for whether the home is overlooking the waterfront or not |
| **view** | rating of home's view, on a scale of 0 to 4 |
| **condition** | overall condition of each home, on a scale of 1 to 5 |
| **grade** | overall grade given to each home, on a scale of 1 to 13, based on King County grading system. 1-3 falls short of buidling construction and design, 7 has an average level of construction and design, and 11-13 has a high quality level of construction and design |
| **sqft_above** | square footage of the interior housing space, excluding basement |
| **sqft_basement** | square footage of the basement |
| **yr_built** | year that each home was built |
| **yr_renovated** | year of each home's last renovation |
| **zipcode** | zip code in which home is located |
| **lat** | latitude coordinate |
| **long** | longitude coordinate |
| **sqft_living15** | square footage of interior housing living space for the nearest 15 neighbors |
| **sqft_lot15** | square footage of the land lots of the nearest 15 neighbors |


## Results
- ***insert results here***
- put **visualizations** here
- along with inerpretaions of final model

## Conclusions
- ***insert results here***
- this section may not be necessary?

## For More Information

See the [full model process](https://github.com/sidneykung/Housing_Price_Model/blob/master/modeling_process.ipynb) in a Jupyter Notebook, named `final_modeling_process.ipynb`, located in this repository.

For additional info, contact Sidney Kung at sidneyjkung@gmail.com