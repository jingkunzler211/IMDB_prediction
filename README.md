# IMDB_prediction by Jing Kunzler

## Original data source
* https://github.com/sundeepblue/movie_rating_prediction
* 5043 movies

## Raw Data Schema

![image](https://user-images.githubusercontent.com/34362014/138983758-57e5e3cd-90b1-434c-a28e-75ebe4e1a94f.png)

## PART 0: DATA PREPROCESSING

* Check notebook "Pre-processing"
* written transformed df to csv (version 1)

## PART 1: EDA, VISUALIZATION & MISC DATA TRANSFORMATION

* Check notebook "EDA & Visualization"
* written further transformed df to csv (final version): check clean_imdb_2.csv

## PART 2: FEATURE ENGINEERING & REGRESSION MODELING

* Check notebook "Regression"

* Feature selection & engineering 
    * Dummie variable
    * Normalization

* Algorithms (*evaluator = mean squared error*)
    * KNN (*Okay*)
    * SGD Regressor (*Worst*)
    * Random Forest (*Best*)
    * Gradient Boosting Regressor (*Runner up*)

* Feature Importance with the best model (RF)
