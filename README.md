
# Prediction of restaurant ratings

Semester project by Team Tissot:   

**LAUX** David  
**RANDIN** Samuel   
**SOLONIN** Maksim  
**VIVARIE** Romin  

Professor: **VLACHOS** Michalis

## About the project
In this Notebook, we will present you the reasons that can influence - positively or negatively - a restaurant's rating on Yelp.

## Structure Project


### /code
Contains the different codes necessary for the realization of this project, namely:

***Data Pre-processing.ipynb*** : contains the extraction of the attributes of business out of raw data and converts them into readable data format 

***DataCleaning.ipynb***: contains the cleaning version of the datasets. extract features

***EDA.ipynb***: contains the exploration data analysis

***Main.ipynb***: contains the main Notebook.


### /data
The folder contains the original versions of datasets as well as the cleaned version. The raw dataset includes information about local businesses in 10 metropolitan areas across 2 countries.
You can find the original dataset [here](https://www.yelp.com/dataset/challenge)

Here is a short explanation of the main features of this dataset :
* *is_open* - binary showing, whether a restaurant is permanently closed
* *latitude* - geographical location (latitude) of the restaurant
* *longitude* - geographical location (longitude) of the restaurant
* *name_length* - length of the name of the restaurant
* *Price* - price category(1 - least expensive, 4 - most expensive)
* *Anymusic* - if music is available in the restaurant (DJ, live, etc.)
* *review_count* - number of reviews on YELP for a restaurant
* *Cuisines* - many TRUE/FALSE features for cuisine types
* *stars* - dependent variable (star rating of the restaurant from 1 to 5)
### /document
In this folder you can find: 
  
***project-instructions.pdf***: contains the instructions for the project
***Project-Main.pdf***: pdf version of the main notebook of the project
