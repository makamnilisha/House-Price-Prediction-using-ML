# House Price Prediction using Machine Learning

According to Zillow, home prices increased by 23% between 2020 and 2022. In addition, the current economic conditions have resulted in uncertainty in the housing market, causing a constant fear in the buyer's mind to pay more than the suitable price. This study aims to provide the most accurate price prediction possible for homes to assist prospective purchasers in making the best selections possible.
  
  Previous studies offered effective machine learning models to help estimate the prices. Still, they focused on analyzing only a few external neighborhood features of the house. However, this research includes more variables, including income,  GDP per capita, GDP, the neighboring schools, and crime ratings
  
# About the Dataset
Five datasets containing house characteristics, school ratings, crimes, GDP, and GDP per capita were collected for the project.
*Web Scraping was performed to collect houses and school ratings dataset from zillow and greatschools.org respectively*
The GDP dataset was collected from Bureau of Economic Analysis (BEA) website, and finally Crime dataset was taken from the FBI website.

We used 4 major machine learning models : XGBoost, Random Forest (RF), K-Nearest Neighbour (KNN), Artificial Neural Networks (ANN) and a *new ensemble model which is created by merging XGBoost and ANN* in our project. For accuracy, the R2, RMSE, and MAE have been calculated for each model. 

# Results
The new ensemble model, which is an amalgamation of XGBoost and ANN, was the chosen model for deployment owing to its performance with an R-squared score of 75%. It is also important to note that the new ensemble has the best R2 score, surpassing RF and ANN. Also, among all the other four models, KNN gave less performance with a 0.62 accuracy. Finally, this project's objective was met through this work by exploring the application of different machine learning approaches to predicting the price of homes.

# Future Scope
The Future scope of this project is to build a user interface and also try to implement different neural networks and experiment.

Technologies Implemented : *Web scraping using requests and beautiful soup, Jira, Python - Pandas, Numpy, scikitlearn, matflotlib, tensorflow, Dimesion reduction using PCA, EDA using Tableau*

Project was performed using crisp-dm process. Also used Gantt and PERT chart for effort estimation

![image](https://user-images.githubusercontent.com/38915458/209068805-f4005173-ab2f-4f09-acc4-ef400b4ac6a3.png)
