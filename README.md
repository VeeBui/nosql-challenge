# noSQL-challenge
Violet Bui - Data Bootcamp - Module 12 challenge

## Project
Two Jupyter Notebooks to analyse restaurants from a provided json file.

## Resources:
<u>/Resources/establishments.json</u> - The data imported - A json file with many restaurants and 

## Part 1 and 2: Database set up | Updating of the databse
Initial exploration of the mongoDB database imported from the json file and insertion of new resturant document, into collection. 

Variable types have been cast correctly and establishments from Dover were removed.

### Solutions created:
- <b>NoSQL_setup_starter.ipynb</b>: Jupyter notebook containing code to set-up and clean database and insert new restaurant into the database


## Part 3: Exploratory Analysis
Analysis of establishments to avoid, provided for "<i>Eat Safe, Love</i>"

### Solutions created:
- <b>NoSQL_analysis_starter.ipynb</b>: Jupyter notebook providing answers to analysis of establishments to avoid


### Queries
1) Which establishments have a hygiene score equal to 20? (lowest hygiene)    
2) Which establishments in London have a RatingValue greater than or equal to 4?
3) What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?
4) How many establishments in each Local Authority area have a hygiene score of 0?
