# Kaggle: must-do list

## Data Preprocessing

- accelerate file IO: convert csv data to hdf5 or binary formatted file.  
- impute missing data
- reduce duplicates ( and convert duplicating counts to features)
- remove non-representative samples (subsets that are not helpful in building models that generalize in the test data). 

## Data Explorative Analysis

- categorical features: calculate mutual information with labels
- numeric features: plot 1D distributions of different labels along each dimension.
- date features:

## Model Setup

- examine train/test split, and create local validation w.r.t. that.
- separate codes for feature engineering and model learning. 
- choose the proper model to start with: XGB or RandomForest.

## Feature Engineering

- leave-one-out for categorical features (of high cardinality)
- one-hot for categorical features of low cardinality.
- create meaningful stratum, and treat it as a categorical variable
- build dictionary learning for numerical features (of low dimensions)
- feature selection: 
