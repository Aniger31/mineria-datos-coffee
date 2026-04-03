# Practica 6 - Classification (KNN)

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre producción, consumo, importación y exportación de café en distintos países y años.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Datos de 94 países

## Objetivo

El objetivo de esta práctica es construir un modelo de clasificación utilizando el algoritmo K-Nearest Neighbors (KNN) para clasificar los registros en categorías de alta o baja producción de café.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Creación de una variable categórica llamada *high_production*, donde:
   - 1 representa alta producción
   - 0 representa baja producción
3. Selección de variables relevantes:
   - Producción
   - Consumo doméstico
4. División de los datos en conjunto de entrenamiento y prueba.
5. Construcción del modelo KNN con 5 vecinos.
6. Generación de predicciones.
7. Evaluación del modelo mediante la métrica de precisión (accuracy).

## Resultados

- Se obtuvo una precisión (accuracy) de 0.9967.
- El modelo clasifica correctamente aproximadamente el 99.67% de los datos.
- Esto indica un desempeño muy alto del modelo.

## Conclusiones

El modelo KNN mostró un excelente desempeño al clasificar los datos en alta y baja producción de café.

La alta precisión sugiere que las variables utilizadas permiten diferenciar claramente entre las categorías.

Sin embargo, también puede indicar que el problema es relativamente sencillo o que existe una fuerte relación entre las variables utilizadas.

Este modelo servirá como base para técnicas más avanzadas en las siguientes prácticas, como clustering y predicción.
