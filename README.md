# Spanish-Wine-Price-Prediction
ML- Supervised - Regression
![2254](https://user-images.githubusercontent.com/83806097/229751925-a665efef-defe-49c9-a575-c45f5142ec10.jpg)
# Problem Statement
This dataset is related to red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The classes are ordered and not balanced. The task is to predict the prices of wine using the given data.
## Data Description
The dataset contains 7500 different types of red wines from Spain with 11 features that describe their price, rating, and even some flavor description. This study reviewed the literature and used the following 11 variables as explanatory variables:
- winery: Winery name
- wine: Name of the wine
- year: Year in which the grapes were harvested
- rating: Average rating given to the wine by the users [from 1-5]
- num_reviews: Number of users that reviewed the wine
- country: Country of origin [Spain]
- region: Region of the wine
- price: Price in euros [€]
- type: Wine variety
- body: Body score, defined as the richness and weight of the wine in your mouth [from 1-5]
- acidity: Acidity score, defined as wine's “pucker” or tartness; it's what makes a wine refreshing and your tongue salivate and want another sip [from 1-5]
## Data Pipeline
- Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.
- Data Preprocessing: In this part we went through each attributes and encoded the categorical features using pipeline.
- Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so that we can get the best performing model for our project.
# Project Files Description
This Project includes 1 Jupyter notebook and 1 Pdf of presentation.
- [Spanish Wine Price Prediction](https://github.com/AnkitaD1998/Spanish-Wine-Price-Prediction/blob/main/Wine%20price%20prediction.ipynb) - Includes Exploratory Data Analysis and all algorithms which are used in this project.
- [Spanish Wine Price Presentation](https://github.com/AnkitaD1998/Spanish-Wine-Price-Prediction/blob/main/Spanish%20Wine%20Price%20Prediction%20Project.pdf) - Includes pdf of the presentation of the project.
## Execution Instruction
The order of execution of the colab notebook is as follows:
1) _Spanish Wine Price Prediction.ipynb_

First, click on the Spanish Wine Price Prediction, which is our working notebook.
In this .ipynb file, we have -
- EDA on Spanish Wine Price prediction.
- Outliers detection.
- converting categorical variables into numerical variables using encoder and passing through it into pipeline.
- Fitting different models through pipeline.
2) _Kaggle Dataset_

Downlaod the dataset from kaggle through provided link.Then, upload the dataset into the notebook and connect.
# Algorithms
1. Linear Regression
2. Lasso Regression
3. Ridge Regression
4. Elastic net Regression
5. Decision Tree Regression
6. Random Forest Regression
7. Gradient Boosting Regression
8. Xtreme Gradient Boosting
# Conclusion
- When we compare the root mean squared error and mean absolute error of all the models, the _Random forest regression_ model has less root mean squared error & mean absolute error, ending with the _R-squared of 97%_. So, finally this model is the best for predicting the price of Spanish wine.        
- The top key features that drive the price of the wine are: rating, year, wine, acidity, num_reviews.
- The above data is also reinforced by the analysis done during bivariate analysis.


