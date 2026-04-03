# Practica 1 - Data Cleaning

## Dataset
Se utilizó el dataset Coffee Distribution Across 94 Countries.

El dataset contiene:
- 6016 registros
- 21 variables
- Información sobre producción, importación, exportación y consumo de café por país y año.

## Proceso de limpieza

Se realizaron los siguientes pasos:

1. Carga del dataset usando Pandas.
2. Exploración de la estructura de datos con df.info() y df.describe().
3. Verificación de valores nulos con df.isnull().sum().
4. Revisión de duplicados con df.duplicated().sum().
5. Normalización de nombres de columnas (minúsculas y sin espacios).
6. Guardado del dataset limpio para análisis posteriores.

## Resultados

- No se encontraron valores nulos.
- No se encontraron registros duplicados.
- Los nombres de las columnas fueron estandarizados.

