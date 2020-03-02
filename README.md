------------------------------
# kaggle_project 
------------------------------

El objetivo de este proyecto es utilizar diferentes modelos que nos ayuden a predecir el precio de los diamantes. 


## Hipótesis:

                                   "¿Cuál es el precio de diamantes?"

## Input:
  - kaggle --> Diamonds:
      o Diamonds_train.csv
      o Diamonds_test.csv

## Output:
  - Model1:
      o LinearRegression con todas las 'features'.
      o R2_score = 0.88

  - Model2:
      o RandomForest: 
        Se entrena el modelo de distintas opciones: reduciendo el número de 'features', con todas y variando los parámetros del modelo.

  - Model3:
      o LinearSVR(),
      o LinearRegression(),
      o RandomForestRegressor(n_estimators=100),
      o RandomForestRegressor(n_estimators=200),
      o DecisionTreeRegressor(random_state=0),
      o KNeighborsRegressor(),
      o GradientBoostingRegressor(),
      o HistGradientBoostingRegressor()

  - Model4:
      o RandomForest con una variación en la preparación de los datos.
