# Taquilla_Cine

![](https://github.com/adryCrespo/Taquilla_Cine/Movies.jpg)

Este proyecto trata de predecir la recaudacion de películas. Para ello usa datos de muchos tipos como economicos, temporales, de cast de personajes , etc...
De esta forma este proyecto se enmarca dentro de un framework de un problema de regresión de machine learning.


Los datos para el desarrollo del modelo proceden de un concurso kaggle de 2019 ([Link](https://www.kaggle.com/competitions/tmdb-box-office-prediction/overview) )
Los datos de entrenamiento tienen 3000 filas y 23 variables. La mayor complicación a la hora del procesamiento es que alguna de las variables viene en formato json. Además, muchas de las variables numericas muestran distribuciones con largas colas.

De entre todas las opciones que se han barajado para los algoritmos usaremos XGBoost.

Se han realizado dos modelos:
El modelo modelo 1 usa datos de variables y conteo de categoricas, mientras que el modelo 2 usa la sinopsis de las películas para enriquecer los datos.
En ambos modelos se han probado varias opciones pero finalmente hemos utilizado el algoritmo XGBoost.

De entre todas las variables se ha encontrado que el propio presupuesto de las peliculas es el factor más determinante en la recaudación de la misma. Además usar palabras claves en la sinopsis mejora la recaudación al llamar más la atención de posiblems usuario

