# PIA - Minería de Datos  
## Patrones y Tendencias en la Producción y Consumo de Café

## Descripción del Proyecto

El presente proyecto tiene como objetivo analizar los patrones y tendencias en la producción y consumo de café a nivel mundial, utilizando técnicas de minería de datos para transformar datos en información útil para la toma de decisiones.

## Dataset

Se utilizó el dataset *Coffee Distribution Across 94 Countries*, el cual contiene información sobre:

- Producción de café
- Consumo doméstico
- Importaciones y exportaciones
- Inventarios

Características del dataset:
- 6016 registros
- 21 variables
- Información de 94 países a lo largo del tiempo

## Metodología

Para el desarrollo del análisis se aplicaron diversas técnicas de minería de datos:

1. **Limpieza de datos (Data Cleaning)**  
   Se preparó el dataset eliminando inconsistencias y estandarizando los nombres de las variables.

2. **Estadística descriptiva**  
   Se analizaron las principales características del dataset para entender su estructura.

3. **Visualización de datos**  
   Se generaron gráficas para explorar relaciones y patrones.

4. **Pruebas estadísticas**  
   Se aplicaron pruebas como ANOVA y T-test para identificar diferencias significativas.

5. **Modelos de regresión**  
   Se evaluó la relación entre producción y consumo mediante regresión lineal.

6. **Clasificación (KNN)**  
   Se clasificaron los datos en niveles de producción, obteniendo alta precisión.

7. **Clustering (K-Means)**  
   Se agruparon los datos en clusters para identificar perfiles de países.

8. **Forecasting**  
   Se analizó la tendencia temporal y se realizaron predicciones futuras.

9. **Análisis de texto**  
   Se analizaron los países más representados mediante una word cloud.

## Resultados

- Se identificó una **relación débil** entre producción y consumo (R² = 0.14).
- El modelo de clasificación obtuvo una **precisión del 99.67%**, indicando patrones claros.
- Se identificaron **3 grupos principales de países** mediante clustering.
- Se observó una **tendencia creciente** en la producción de café.
- Se detectó una **concentración geográfica** en ciertos países.

## Conclusiones

El análisis permitió identificar que, aunque la producción de café ha aumentado con el tiempo, no existe una relación fuerte con el consumo.

Sin embargo, se encontraron patrones claros que permiten clasificar y segmentar los países, lo que resulta útil para la toma de decisiones en el mercado del café.

Las técnicas de minería de datos aplicadas demostraron ser herramientas efectivas para transformar datos en conocimiento.

## Contenido de la carpeta

- `presentacion.pptx` → Diapositivas utilizadas en el video  
- `video.mp4` o `link_video.txt` → Video de presentación del proyecto  
- `README.md` → Descripción del proyecto  

## Nota

El código completo de las prácticas se encuentra en las carpetas correspondientes dentro del repositorio.
