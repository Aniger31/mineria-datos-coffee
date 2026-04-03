# Practica 7 - Clustering (K-Means)

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre producción, consumo, importación y exportación de café en distintos países y años.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Datos de 94 países

## Objetivo

El objetivo de esta práctica es aplicar el algoritmo K-Means para agrupar los datos en clusters y descubrir patrones ocultos en la relación entre la producción y el consumo de café.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Selección de variables relevantes:
   - Producción
   - Consumo doméstico
3. Aplicación del algoritmo K-Means con 3 clusters.
4. Asignación de cada registro a un cluster.
5. Visualización de los clusters mediante una gráfica de dispersión.
6. Análisis de los centroides generados por el modelo.

## Resultados

- Se identificaron tres clusters principales en los datos.
- Un grupo con baja producción y alto consumo.
- Un grupo con baja producción y bajo consumo.
- Un grupo con alta producción y consumo medio-alto.
- Los clusters se visualizan claramente en la gráfica, mostrando una separación adecuada entre grupos.

## Conclusiones

El modelo de clustering permitió identificar diferentes perfiles dentro del dataset, lo que facilita la comprensión del comportamiento de los países en términos de producción y consumo de café.

Este tipo de análisis es útil para segmentar datos y encontrar patrones que no son evidentes a simple vista.

Los resultados obtenidos pueden servir como base para análisis más avanzados en la toma de decisiones.
