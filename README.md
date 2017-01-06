# Allstate Claims Severity project

This project provides a sample solution to [Allstate Claims Severity competition](https://www.kaggle.com/c/allstate-claims-severity) on Kaggle. 

* **[Part 1: Data Disvovery](part1_data_discovery.ipynb)** Basic data analysis. Similar analysis can be found at [dnkirill's data discovery](https://github.com/xujin1982/allstate_capstone/blob/master/part1_data_discovery.ipynb) and [Santhosh Sharma's exploratory study](https://www.kaggle.com/sharmasanthosh/allstate-claims-severity/exploratory-study-on-ml-algorithms#).
* **[Part 2: XGBoost model training and tuning](part2_XGBoost_traininig_and_tuning.ipynb)** Show a framework step by step for hyper-parameters optimization of [XGBoost](xgboost.readthedocs.io/en/latest/) based on [Bayersian Optimization](https://github.com/fmfn/BayesianOptimization).
* **[Part 3: LightGBM model training and tuning](part3_LightGBM_training_and_tuning.ipynb)** Show a framework step by step for hyper-parameters optimization of [LightGBM](https://github.com/Microsoft/LightGBM) based on [Bayersian Optimization](https://github.com/fmfn/BayesianOptimization).
* **[Part 4: ANN model training and tuning](part4_ANN_Keras_training_and_tuning.ipynb)** A simple example for parameters tuning of ANN model. 
* **[Part 5: Final result with blending and stack](part5_blending_and_stack.ipynb)** Combine predictions of XGBoost, LightGBM and ANN with two linear functions, [Ridge](http://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html) and [XGBoost gblinear](http://xgboost.readthedocs.io/en/latest/parameter.html).

## Requirements

### Dataset

The dataset is available for free on [Kaggle's competition page](https://www.kaggle.com/c/allstate-claims-severity/data).

### Software

This project uses the following software (if version number is omitted, latest version is recommended):

* **[Python stack](https://docs.continuum.io/)**: python 2.7, numpy, scipy, sklearn, pandas, matplotlib.
* **[XGBoost](http://xgboost.readthedocs.io/en/latest/model.html)**: XGBoost is short for “Extreme Gradient Boosting”, where the term “Gradient Boosting” is proposed in the paper Greedy Function Approximation: A Gradient Boosting Machine, by Friedman.
* **[LightGBM](https://github.com/Microsoft/LightGBM)**: A fast, distributed, high performance gradient boosting (GBDT, GBRT, GBM or MART) framework based on decision tree algorithms, used for ranking, classification and many other machine learning tasks.
* **[Keras](https://keras.io/)**: Keras is a high-level neural networks library. It is shown in the [post](http://machinelearningmastery.com/develop-evaluate-large-deep-learning-models-keras-amazon-web-services/) that how to access to GPUs to speed up the training of the deep learning models by using the Amazon Web Service (AWS) infrastructure.
* **[BayesianOptimization](https://github.com/fmfn/BayesianOptimization)**: A Python implementation of global optimization with gaussian processes. 
