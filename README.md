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

2. Customized evaluation matric(scoring):
- RMSLE: ![Alt text](https://raw.githubusercontent.com/gogowenzhang/Predictive-Model-Pipeline/master/img/rmsle.png)



3. Customized cross validation split:
- Split training and test data by datetime. 

4. Tuned hyperparameters with GridSearch.


### How to Run:
Package Dependencies:
- numpy==1.13.1
- pandas==0.19.2
- sklearn==0.18.1

Execution:
Install required packages, unzip Train data and invoke:
```
$ python src/price-prediction-model.py
```

