Environment :-
jupyter notebook and google colab.
surprise package

Dataset:-
we used movielens 1 million dataset. Link is attached below.
https://grouplens.org/datasets/movielens/1m/
From the dataset, we used 2 files for the project. They are:-
1) ratings.dat
2) movies.dat

code and files:-
train_test_division.ipynb :- This file is used to divide our date into train.csv and test.csv
exploratory_data_analysis.ipynb :- This file takes input as ratings and movies data and performs exploratory data analysis.
models_surprise.ipynb :- This file takes training and testing data and all models (except ALS and nueral net) are trained  and tested in this 	file and saves each model prediction data as csv file.
recommendation_neural_network.ipynb :- This file performs neural net training and testing and returns neural net predictions as csv file.
ALS_recommendation.ipynb :- This file performs ALS method training and testing and returns ALS predictions as csv file and performs metrics evaluation for ALS model.
Ensemble_method.ipynb :- This file calculates ensemble ratings and returns ensemble predictions as csv file.
metrics_all_models.ipynb :- This file calculates metrics for all models taking each model prediction file as input.

