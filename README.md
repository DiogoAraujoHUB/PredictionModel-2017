## Project Details
This project was created using Python for the "Aprendizagem Automática" class.

Made by: Diogo Araújo - 60997


## Project Summary
The objective of this project was to use three datasets to create the best regression model capable of predicting values for a year we have no data on. For this project, we have datasets which have data up until the year 2016. The purpose of the models is to use that data to predict values for the year 2017.

For this, we had to process the data, select the best model, predict the values for the year (model results) and then discuss these values. 


## Data Processing
The processing of the data involved creating new dataframes which include their delta values, which consist of the value of the next year subtracted by the value of the current year.

![image](https://github.com/DiogoAraujoHUB/PredictionModel-2017/assets/61624282/6aa195b3-791b-43c9-8811-eba56e9ea8ff)


## Model Selection
For the model selection, we picked between three different models. These being Linear Regression, K-Nearest Neighbors and the Random Forest model. They were evaluated by comparing their R2 score metric for each dataframe, with the highest being picked.

![image](https://github.com/DiogoAraujoHUB/PredictionModel-2017/assets/61624282/036f0b48-b702-4b8e-9193-a7e123ac1380)

## Model Results
This is a display of the model predictions being compared to their actual values.

![image](https://github.com/DiogoAraujoHUB/PredictionModel-2017/assets/61624282/1eb25a5b-6d27-4899-b4bb-9eebc3cbf1cc)

