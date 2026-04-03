# Practica 2 - Descriptive Statistics

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre la producción, consumo, importación y exportación de café a lo largo del tiempo.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Información de 94 países

## Objetivo

El objetivo de esta práctica es realizar un análisis estadístico descriptivo del dataset para identificar patrones, tendencias y relaciones entre variables.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Obtención de estadísticas descriptivas con `df.describe()`.
3. Cálculo de métricas como promedio de producción y consumo.
4. Agrupación de datos por país y por año utilizando `groupby()`.
5. Identificación de los países con mayor producción de café.
6. Análisis de la relación entre producción y consumo mediante correlación.
7. Generación de gráficas para visualizar los resultados.

## Resultados

- Brasil es el país con mayor producción promedio de café.
- Se identificaron diferencias significativas en la producción entre países.
- La producción de café presenta variaciones a lo largo del tiempo.
- Existe una relación entre la producción y el consumo de café.

## Conclusiones

El análisis descriptivo permitió entender mejor la distribución de la producción de café a nivel mundial.  
Estos resultados servirán como base para análisis más avanzados en las siguientes prácticas, como modelos predictivos y clustering.
