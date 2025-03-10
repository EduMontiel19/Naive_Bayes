# Naive_Bayes

## Objetivo
El propósito de esta actividad es que los estudiantes busquen, seleccionen y analicen un conjunto de datos en Kaggle o en otra fuente confiable, aplicando el algoritmo de Naïve Bayes para resolver un problema de clasificación. Además, deberán presentar los resultados y conclusiones obtenidas, relacionándolos con la teoría del Teorema de Bayes.

### Descripción de la Actividad
En esta actividad se realizó un análisis e implementación del clasificador Naïve Bayes, abarcando desde la teoría hasta la aplicación práctica utilizando un conjunto de datos obtenido de Kaggle.
1. Búsqueda y Selección de Datos en Kaggle

Se accedió a la plataforma Kaggle para buscar un conjunto de datos adecuado para la aplicación del algoritmo de Naïve Bayes. Se seleccionó un dataset con una variable de salida categórica y al menos tres características relevantes para la clasificación. La elección del dataset se justificó con base en su adecuación al modelo Naïve Bayes.

2. Preprocesamiento de los Datos

Para garantizar la calidad de los datos, se realizaron los siguientes pasos:

Carga del dataset utilizando bibliotecas como pandas y sklearn.

Limpieza y tratamiento de valores nulos.

Codificación de variables categóricas si fue necesario.

División de los datos en conjuntos de entrenamiento (80%) y prueba (20%) para evaluar el rendimiento del modelo.

3. Aplicación del Algoritmo de Naïve Bayes

Se implementó el algoritmo Naïve Bayes utilizando la biblioteca scikit-learn. El proceso incluyó:

Entrenamiento del modelo con los datos de entrenamiento.

Evaluación del modelo con el conjunto de prueba.

Cálculo de métricas de desempeño como precisión, recall y matriz de confusión para medir la efectividad del clasificador.
