# machine-learning-challenge

This project utilizes data from the NASA Kepler space telescope used to discover potential hidden planets located outside of our solar system ("exoplanet_data.csv"). Within "serena_baker.sav" you will find the file containing the best machine learning model created in order to process the data.

In order to analyze the models I preprocessed the dataset by: Dropping null values and columns. I then performed feature selection by comparing Decision Tree and Random Forest classifiers and chose the four highest weighted classifiers from RF (Best rated score). I then used MinMaxScaler to scale the data and separated the data into train/test data.

I then compared the models and used GridSearch to tune the model parameters.