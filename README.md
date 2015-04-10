[Kaggle otto classification problem](http://www.kaggle.com/c/otto-group-product-classification-challenge)


## Approach
- Played around and tested RF and BT algos in sklearn. Ended up somewhere around top 500 in LB
- xgboost library allowed faster iterations, set up grid search for parameters and got to top 200 (10%) on LB (at point of writing)

## Initial observations
- Dataset small
- seems like no missing values (?)

## Files
- train.csv, test.csv, sampleSubmission.csv - Kaggle data files 
- general.ipynb - initial tests with data and some sklearn libraries
- xgboost.ipynb - work with xgboost
- output\*.csv - output files

