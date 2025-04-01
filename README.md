# Depresi-n-en-estudiantes-indios
Trabajo final de Samsung Innovation Campus 2024
## Depresi-n-en-estudiantes-indios
Trabajo final de Samsung Innovation Campus 2024
# PROYECTO FINAL "Depresión en Estudiantes De La India"



En este proyecto trabajamos con datos sobre la depresión en estudiantes indios, para poder obtener datos que nos ayudarán a poder auxiliarlos y probablemente reducir la tasa de suicidios, con esto se abre una puerta a proyectos futuros en diferentes países.

Para ello, Primero se limpió el dataset y nos quedamos con las columnas que tenian datos diferentes, también, borramos los outliers para que los modelos tuvieran mayor presición.

Posteriormente, obtuvimos la matriz de confusión, utilizamos un encoded en base a la matríz y clasificamos a cerca de los estudiantes en depresión. Después, buscamos variables a que pudieramos utilizar para agrupación con diferentes métodos que fueron el modelo de mezcla gaussiana y DBSCAN 

Con estos modelos podemos poner a prueba nuestras habilidades y conocimientos obtenidos mediante el curso, con el objetivo de obtener un modelo de regresión, un modelo de agrupamiento y un modelo de clasificación.

Como principales funcionamientos del sistema tenemos:
- Limpieza de datos
- Clasificación
- Agrupamiento 
- Regresión

Para lograrlo utilizamos bibliotecas como:
- numpy
- pandas
- matplotlib
- seaborn
- sklearn 
    - svm 
    - RandomForestClassifier
    - LogisticRegression
    - GaussianMixture
    - DBSCAN
    - DecisionTreeClassifier
    - GradientBoostingClassifier
    - KNeighborsClassifier
    - GaussianNB
Y para obtener hiper parametros:
- GridSearchCV
 
### Pasos para clonar y ejecutar el proyecto en local.
Asegurate de tener los datos crudos en la misma carpeta que los Notebooks

Requisitos previos: Para compilar el programa debes asegurarte de tener todas las librerías mencionadas, el programa fue compilado en python 3.12.9 y el otro en Google collab 
