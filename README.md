# Prediction of Used Car Prices with Gradient Boosting Regressor

## About this project: 
- This project comes from the competition that i participated on Kaggle website. The details about the project is in [this link](https://www.kaggle.com/competitions/playground-series-s4e9/overview).

- The main idea about this project is to predict the price of used car based on characteristics like brand name, color, engine,...

## Used Python libraries/packages - requirements of installation before running the notebook: 
1) kaggle
- To interact with Kaggle API, making it possible to download datasets directly from Kaggle's competition.
  
2) os
- To interact with operating system, manage files, directories.

3) Pandas 
- To read CSV files.
- To deal with missing values.
- To perform some DataFrame operations like "drop()", "select_dtypes()".

2) Seaborn/ Matplotlib
- To visualize the data.
- To customize the plot.

3) category_encoder
- Encoding categorical variables/ columns in dataframe because Machine Learning models require numerical inputs. 

4) Scikit-Learn
- To split the data into train and test sets.
- To fill missing values with startegies like "mean" or "most frequent" (from "SimpleImputer").
- For encoding categorical variables/features into numerical values.
- For feature scaling (normalizing data in this case from "MinMaxScaler").
- For evaluating the model (in this case it's mean squared error - MSE)

5) pycaret
- To get details about the data used to train the model.
- Making it possible to compare several regression models (since it's regression task for this competition), choose the best one and tune it, finally evaluate it. 

## The result for the project
- At the end of the project, a csv file which contains two columns "id" and "class"(filled with predictions from the model) must be exported and submitted to the competition. 
- The score obtained for this competition is the root mean squared error of the trained model to predict on 125690 used cars. 
![image](https://github.com/user-attachments/assets/81639918-62aa-48fa-a25c-68c22d877efd)

