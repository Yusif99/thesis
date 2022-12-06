# Code of my Master's degree thesis, "Soil Organic Carbon Prediction with Machine Learning".
[Research Paper](https://docs.google.com/document/d/1cm-DQw9IFj3zx_Ks2o7ktYnRbjkdXq4xM2N5tj7AF5I/edit#).
I have built several models via Random Forest Regressor technique for predicting Soil Organic Carbon (SOC) in Estonia. The differences between the models were covariates, sampling data, and feature elimination methods.
The general RF model-building workflow for the current study is described below:

* Splitting preprocessed data (70% train, 30% test)		

* Training the basic model (Sklearn) 

* Estimating the accuracy of a basic model

* Hyper-parameter tuning (RandomizedSearchCV)

* Feature elimination and validation of the model

* Training the tuned model

*  Evaluating of Training&Test Model (Sklearn. metrics)

* Analysing Errors/Residuals

* Evaluating the importance of Parameters (Feature Importance, Shapley)

* Executing model on final Dataset

* Data Analysis & Statistics (Seaborn, Matplotlib) 
