# Objective:

- Given a dataset of Starcraft player performance data in ranked games. We want
to develop a model to predict a player’s rank using the information provided in the
dataset.

- Documenting decision making throughout the model building process (EDA, ETL,
modeling, evaluation, etc).

# Approach

## Code
main.ipynb is the file which contains all the analysis

## Archive Code
main_with_feat_eng in the archive_folder can also be checked where model was built using some additional features using additional feature engineering steps. Although the model performance degraded in comparison to the simpler model used in main.ipynb

## Config
- config.ini file contains the path and model related parameters
- Currently load saved model is set to False so that the code runs successfully. 

## Saved Model
As the size of tuned model of hyperopt is more than 100 mb, the trained and tuned model.pkl was added to .gitignore

## Requirements
Run pip install -r requirements.txt in terminal to install all the packages used.

## Run Time
Approximate run time is around 1.5 hours on CPU

# References

- Sklearn, lightgbm, SHAP, PyCaret, optuna and other python packages.
- Wikipedia on certain gaming players trait understanding
 
