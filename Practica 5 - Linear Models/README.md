# Practica 5 - Linear Models + Correlation

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre producción, consumo, importación y exportación de café en diferentes países y años.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Datos de 94 países

## Objetivo

El objetivo de esta práctica es construir un modelo de regresión lineal para analizar la relación entre la producción de café y el consumo doméstico, así como evaluar la fuerza de esta relación mediante el coeficiente de determinación (R²) y la correlación.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Selección de variables:
   - Variable independiente: producción
   - Variable dependiente: consumo doméstico
3. Construcción de un modelo de regresión lineal.
4. Generación de predicciones.
5. Cálculo del coeficiente de determinación (R²).
6. Visualización del modelo mediante una gráfica.
7. Cálculo de la correlación entre variables.

## Resultados

- Se obtuvo un valor de R² de 0.144.
- Esto indica que el modelo explica aproximadamente el 14.4% de la variabilidad del consumo.
- La correlación entre producción y consumo es baja.
- La gráfica muestra una dispersión considerable de los datos.

## Conclusiones

El modelo de regresión lineal muestra que existe una relación débil entre la producción y el consumo de café.

Esto sugiere que la producción no es un buen predictor del consumo y que existen otros factores que influyen en el comportamiento de esta variable.

Estos resultados serán útiles para explorar modelos más complejos en prácticas posteriores, como clasificación y clustering.
