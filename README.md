Code of my Master's degree thesis, "Soil Organic Carbon Prediction with Machine Learning".
I have built several models via Random Forest Regressor technique for predicting Soil Organic Carbon (SOC) in Estonia.
The general RF model-building workflow for the current study is described below:

Splitting preprocessed data (70% train, 30% test)		

Training the basic model (Sklearn) 

Estimating the accuracy of a basic model

Hyper-parameter tuning (RandomizedSearchCV)

Feature elimination and validation of the model

Training the tuned model

Training/Test Model Evaluation (Sklearn. metrics)

Analysing Errors/Residuals

Evaluating the importance of Parameters (Feature Importance, Shapley)

Executing model on final Dataset

Data Analysis & Statistics (Seaborn, Matplotlib) 
