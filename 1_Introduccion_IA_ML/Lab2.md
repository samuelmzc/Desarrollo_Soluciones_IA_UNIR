# Lab 2

El modelo aprende con el *dataset*, el conjunto de datos, que puede tener dos formas:

    - Estructurado: Datos en filas y columnas
    - No estructurado: Imágenes, audios, etc...

También hay dos tipos de aprendizaje:

    - Supervisado: Tenemos una etiqueta correcta en la predicción, y el modelo aprende a llegar a esa etiqueta
    - No supervisado: No existen etiquetas en los datos, el propio modelo descubre grupos
    - Por refuerzo (Reinforcement Learning): El modelo aprende mediante recompensas y castigos

Veamos algunos ejemplos. En el caso de aprendizaje supervisado, tenemos un dataset con correos etiquetados como spam o no spam. Sabiendo esa etiqueta, el modelo aprende de los datos, para, a un input nuevo, clasificarlo como spam o no. Otro ejemplo es para predicción de casas, dado un dataset con casas con sus características y su precio, el modelo ajusta sus modelos para aprender qué precio tendrá una casa según sus características.

En el caso de no supervisado, se tienen modelos de *clustering*, los cuáles agrupan los datos mediante distintos algoritmos, sin ninguna etiqueta previa dada.

### Evaluación del modelo

Lo bueno o malo que es un modelo, se evalúa mediante métricas. Para cada caso, hay métricas más significativas que otras:

    - Clasificación: Precisión
    - Regresión: MAE, MSE, RMSE

$$
h = 2
$$