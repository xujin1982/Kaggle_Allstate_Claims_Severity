# Allstate Claims Severity project

This project provides a sample solution to [Allstate Claims Severity competition](https://www.kaggle.com/c/allstate-claims-severity) on Kaggle. 

* **[Part 1: Data Disvovery](part1_data_discovery.ipynb)** Basic data analysis. Similar analysis can be found at [dnkirill's data discovery](https://github.com/xujin1982/allstate_capstone/blob/master/part1_data_discovery.ipynb) and [Santhosh Sharma's exploratory study](https://www.kaggle.com/sharmasanthosh/allstate-claims-severity/exploratory-study-on-ml-algorithms#).
* **[Part 2: XGBoost model training and tuning](part2_XGBoost_traininig_and_tuning.ipynb)** Show a framework step by step for hyper-parameters optimization of [XGBoost](xgboost.readthedocs.io/en/latest/) based on [Bayersian Optimization](https://github.com/fmfn/BayesianOptimization).
* **[Part 3: LightGBM model training and tuning](part3_LightGBM_training_and_tuning.ipynb)** Show a framework step by step for hyper-parameters optimization of [LightGBM](https://github.com/Microsoft/LightGBM) based on [Bayersian Optimization](https://github.com/fmfn/BayesianOptimization).
* **[Part 4: ANN model training and tuning](part4_ANN_Keras_training_and_tuning.ipynb)** A simple example for parameters tuning of ANN model. 
* **[Part 5: Final result with blending and stack](part5_blending_and_stack.ipynb)** Combine predictions of XGBoost, LightGBM and ANN with two linear functions, [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html) and [XGBoost gblinear](http://xgboost.readthedocs.io/en/latest/parameter.html).
