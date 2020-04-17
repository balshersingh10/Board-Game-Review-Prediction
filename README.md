# Prediction of Board-Game-Review Using Supervised Machine Learning Techniques
We obtained the Board Game Review dataset from **ThaWeatherman's** repository and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of classification techniques like Linear Regression and Random Forest Regression.
## A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are:
- yearpublished
- minplayers
- maxplayers
- playingtime
- minplaytime
- maxplaytime
- minage
- users_rated
- total_owners
- total_traders
- total_wanters
- total_wishers
- total_comments
- total_weights
- average_weight
## B. Model Selection
* Linear Regression
* Random Forest Regressor
## C. Training the models with Data
The data taken is from **www.github.com/ThaWeatherman/scrapers/blob/master/boardgamegeek/games.csv**
## D. Taining Data and Testing Data
80% of above data is training and 20% is testing data.
### Then Average Rating is predicted:
- Anywhere between 1->10
# Result =>
To find the accuracy, Squared Error Function under sklearn library is used.
The Squared Error found is:
- Linear Regression => 2.0788190326293243
- Random Forest Regressor => 1.4458560046071653
## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
- **games.csv(File that conntains Train and Test Data)**  <br />

***In source.ipynb, data is visualized using Histograms and Heat Plots.***
