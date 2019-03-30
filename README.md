# Predict App Success on the Google Play Store using Machine Learning - Decision Trees
UCSD-Edx Python for Data Science MicroMasters Final Project

Dataset: Kaggle Google Play Store Apps https://www.kaggle.com/lava18/google-play-store-apps

## Motivation:

* Gain edge over the industry competition for app success.
* Provide insight for advertisement companies on which apps would generate the most revenue if ads were added.
* Assist Android developers to develop state-of-the-art apps that the public deserve.
## Research Questions: 

1. Can you predict an app's popularity on the Google Play Store using a Decision Tree?
2. If a developer were to create a new app, what qualities should this app have in order to generate the most ad revenue?

## Results
* ~95% Accuracy if using Reviews and Ratings columns. 
* ~72% Accuracy if not using above columns. (More realistic as reviews/ratings will be null if app is not on the Play store.)

## Future Work
* Models which will most likely have better performance are K Nearest-Neighbors, Logistic Regression, and Random Forests. Once implementation of these models are learned, I will commit a change to this repo with the new results from all listed ML models. 

## Requirements
Jupyter Notebook may be used with any OS. 
Ensure you have pip installed the latest versions of the following:
* Pandas
* Numpy
* Seaborn
* Sklearn
* Plotly
* Matplotlib
