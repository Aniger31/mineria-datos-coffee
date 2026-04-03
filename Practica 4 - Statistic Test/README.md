# Practica 4 - Statistical Tests

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre la producción, consumo, importación y exportación de café en distintos países y años.

El dataset cuenta con:
- 6016 registros
- 21 variables
- Datos de 94 países

## Objetivo

El objetivo de esta práctica es aplicar pruebas estadísticas para determinar si existen diferencias significativas entre grupos de datos, específicamente en la producción de café entre los principales países productores.

## Metodología

Se realizaron los siguientes pasos:

1. Carga del dataset limpio (`coffee_cleaned.csv`).
2. Identificación de los tres países con mayor producción promedio.
3. Separación de los datos en grupos según cada país.
4. Aplicación de la prueba ANOVA para comparar los tres grupos.
5. Aplicación de la prueba T-test para comparar dos países.
6. Interpretación de los resultados con base en el valor p.

## Resultados

- En la prueba ANOVA se obtuvo un p-value de 1.74e-30.
- En la prueba T-test se obtuvo un p-value de 1.88e-22.
- Ambos valores son menores a 0.05, lo que indica diferencias estadísticamente significativas.

## Conclusiones

Los resultados de las pruebas estadísticas demuestran que existen diferencias significativas en la producción de café entre los principales países productores.

Esto confirma que la producción de café no es homogénea a nivel global y que ciertos países dominan el mercado.

Estos resultados sirven como base para análisis más avanzados en las siguientes prácticas, como modelos de clasificación, clustering y predicción.
