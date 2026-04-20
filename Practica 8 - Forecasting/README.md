# Practica 8 - Forecasting

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre producción, consumo, importación y exportación de café en distintos países y años.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Datos de 94 países

## Objetivo

El objetivo de esta práctica es aplicar un modelo de regresión lineal para analizar la tendencia de la producción de café a lo largo del tiempo y realizar predicciones para años futuros.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Agrupación de los datos por año para obtener la producción promedio.
3. Construcción de una serie temporal basada en la variable *year*.
4. Aplicación de un modelo de regresión lineal.
5. Generación de predicciones para años futuros.
6. Visualización de los resultados mediante una gráfica.

## Resultados

- Se identificó una tendencia creciente en la producción de café a lo largo del tiempo.
- El modelo de regresión se ajusta adecuadamente a los datos.
- Las predicciones muestran un aumento continuo en la producción para los próximos años.
- Los valores futuros siguen el comportamiento observado en los datos históricos.

## Conclusiones

El análisis de forecasting permitió identificar una tendencia positiva en la producción de café.

Los resultados sugieren que la producción continuará en aumento si se mantienen las condiciones actuales.

Este tipo de análisis es útil para la toma de decisiones y planificación estratégica en el sector cafetalero.
