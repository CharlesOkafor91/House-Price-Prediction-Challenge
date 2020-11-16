# House-Price-Prediction-Challenge
I designed an algorithm to accurately predict the house prices in India. This is a follow up of the challenge in Kaggle. The link to this solution in Kaggle: https://www.kaggle.com/charlesgasper001/notebookdadab2205d
I used Tensorflow for feature engineering, defining my model, Training ad Evaluating
In #FeatureEngineering, I first created an input function that would feed the #Pandas dataframe into our #tensorflow model using the tf.compat.v1.estimator.inputs.pandas_input_fn API.
Next I defined my feature columns using the various feature_columns APIs for the various types of features we had and the hybrid features like the feature crosses used for my latitude and longitude features to help the model get a deeper predicrive abilities beyond what the individual features can provide.
Next I used the FTRL optimizer and RMSE loss function to build the linear regressor
