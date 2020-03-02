------------------------------
# kaggle_project 
------------------------------

El objetivo de este proyecto es utilizar diferentes modelos que nos ayuden a predecir el precio de los diamantes. 


## Hipótesis:

                                   "¿Cuál es el precio de diamantes?"

## Input:
  - kaggle --> Diamonds:
      Diamonds_train.csv
      Diamonds_test.csv

## Output:
  - Model1:
      - LinearRegression con todas las 'features'.
      - R2_score = 0.88

  - Model2:
      - RandomForest: 
        - Se entrena el modelo de distintas opciones: reduciendo el número de 'features', con todas y variando los parámetros del modelo.

  - Model3:
      - LinearSVR(),
      - LinearRegression(),
      - RandomForestRegressor(n_estimators=100),
      - RandomForestRegressor(n_estimators=200),
      - DecisionTreeRegressor(random_state=0),
      - KNeighborsRegressor(),
      - GradientBoostingRegressor(),
      - HistGradientBoostingRegressor()

  - Model4:
      - RandomForest con una variación en la preparación de los datos.
