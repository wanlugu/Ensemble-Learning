# Ensemble-Learning

https://machinelearningmastery.com/tour-of-ensemble-learning-algorithms/

## Bagging Ensemble Learning
Bootstrap aggregation, or bagging for short, is an ensemble learning method that seeks a diverse group of ensemble members by varying the training data. Examples include Bagged Decision Trees (canonical bagging), Random Forest, Extra Trees.
## Stacking Ensemble Learning
Stacking is an ensemble method that seeks a diverse group of members by varying the model types fit on the training data and using a model to combine predictions. Examples include Stacked Models (canonical stacking), Blending, Super Ensemble
## Boosting Ensemble Learning
Boosting is an ensemble method that seeks to change the training data to focus attention on examples that previous fit models on the training dataset have gotten wrong. Examples include AdaBoost (canonical boosting), Gradient Boosting Machines, Stochastic Gradient Boosting (XGBoost and similar)

- XGBoost hyperparameter tuning guide https://www.kaggle.com/code/prashant111/a-guide-on-xgboost-hyperparameters-tuning/notebook. \
- Bayesian optimization guide https://www.kaggle.com/code/prashant111/bayesian-optimization-using-hyperopt/notebook\
  - The idea behind Bayesian optimization is instead of defining a fixed search space, more time is spent in deciding which values to try next. 
  - Parameters are the configuration model, which are internal to the model, it is changed during model training. Hyperparameters are the explicitly specified parameters that control the training process and will stay unchanged. Parameters are essential for making predictions. Hyperparameters are essential for optimizing the model.
