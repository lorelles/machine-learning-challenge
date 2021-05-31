(https://oregon.bootcampcontent.com/Oregon_Coding_Bootcamp/uofo-por-data-pt-12-2020-u-c/-/raw/master/02-Homework/21-MachineLearning/Images/exoplanets.jpg)

# machine-learning-challenge

This project utilizes data from the NASA Kepler space telescope used to discover potential hidden planets located outside of our solar system ("exoplanet_data.csv"). Within "serena_baker.sav" you will find the file containing the best machine learning model I created, the deep neural network sequential linear regression model.

In order to analyze the models I preprocessed the dataset by: Dropping null values and columns, performing feature selection by comparing Decision Tree and Random Forest classifiers, dropping the least impactful feature, and scaling the data using MinMaxScaler to separate the data into train/test sets. I then used GridSearch to tune the model parameters, and finally adjust the test size, features, and classification parameters to find the best fit to compare the models to find the best performing combination.

My first attempted model was the linear regression model which was not nearly as accurate as the linear regression models I created next. In creating the Normal Neural Network I found comparable results to the Deep Neural Network. I attempted to run the model on a smaller subset of features, however I found the greates accuracy when I utilized all but the values labeled "koi_kepmag." Many of these values are interdeterminate upon each other, so perhaps with more time and greater understanding of the dataset I could narrow down an even better performing model. I tried several different train/test sizes, and found an 80% training size to be most accurate while still providing a sufficient test sample size.

The Deep Neural Network model could provide guidance in potential exoplanets however I would like to see greater precision in regards to confirmed cases. Analyzing each of the dataset components to combine metrics that are interdependent and determining the most impactful measurements could help reduce noise and provide greater accuracy going forward.

