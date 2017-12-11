# Predictive Modeling Pipeline

This is a pipeline that takes in training dataset and returns prediction
in csv form. 

### Features: 
1. Customized transformers:
- Convert datatype
- Filter columns that have NaNs
- Replace values and add imputation indicator
- Compute time interval
- Aggregated statistics
- Columns selector

2. Customized evaluation matrix(scoring):
- RMSLE: ![rmsle](Predictive-Model-Pipeline/img/rmsle.png)



3. Customized cross validation split:
- Split training and test data by datetime. 

4. Tuned hyperparameters with GridSearch.


To run this script, unzip datasets and invoke:
```
$ python src/price-prediction-model.py
```

