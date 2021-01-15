My teammate and I trained a prediction model, which could take a song, and by its characteristics (like loudness, explicit/not, tempo, danceability, etc) could predict if the song would reach the top 50 charts in Spotify. We used Python as our language of choice, preprocessed and used various ML and ensemble algorithms to train our dataset.

Dataset used: https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks

Class Label: popornot (recreated class label, derived from popularity

Dimensions: (170653, 19)
Algorithms applied to test prediction: KNN, DT, RFC, Logistic Regression, SGDC, Bagging (with DT), Adaboost, Adaboost+RFC, Gradient Boost, XGBoost, Stacking with MetaClassifier (DT, RFC and logistic regression)

XGBoost gave us the highest performance accuracy (80.48%) and ROC AUC (79.48%). 

