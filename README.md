# Análisis de Datos Musicales de Spotify: Dimensionalidad y Clustering

Este repositorio contiene dos análisis detallados sobre un conjunto de datos de canciones de Spotify, explorando técnicas de reducción de dimensionalidad y clustering. El objetivo principal es extraer información valiosa sobre la estructura de los datos musicales y cómo se pueden agrupar las canciones según sus características.

## Contenido

1.  **Reducción de Dimensionalidad (`spotify_dimensionalidad.ipynb`)**

    * Exploración de técnicas de selección y extracción de características para simplificar la representación de los datos.
    * Métodos aplicados:
        * Umbral de Varianza
        * Eliminación por Correlación
        * SelectKBest y Chi-cuadrado
        * Sequential Feature Selector
        * Principal Component Analysis (PCA)
        * t-SNE
        * UMAP
    * Evaluación del impacto de la reducción de dimensionalidad en el rendimiento de un modelo de clasificación (RandomForestClassifier).

2.  **Clustering (`spotify_clustering.ipynb`)**

    * Aplicación de algoritmos de clustering para identificar grupos de canciones con características similares.
    * Métodos aplicados:
        * BIRCH
        * K-Means
    * Evaluación de la calidad del clustering mediante el coeficiente de silueta.
    * Discusión sobre la importancia de considerar factores contextuales y del consumidor en el análisis de datos musicales.

## Objetivo

Este análisis busca demostrar la aplicación práctica de técnicas de reducción de dimensionalidad y de clustering. Los resultados pueden ser útiles para diversas aplicaciones, como la recomendación de música, la segmentación de audiencias y la comprensión de las tendencias musicales.

## Cómo Utilizar este Repositorio

1.  Clona el repositorio.
2.  Asegúrate de tener instaladas las librerías necesarias (ver `requirements.txt` en cada notebook).
3.  Ejecuta los notebooks en orden para seguir el flujo del análisis.
4.  Adapta el código y los análisis a tus propias necesidades y explora nuevas ideas.

## Autor

\[Jorge Moltó]

* \[[LinkedIn](https://www.linkedin.com/in/jorgemoltomolto/)]

---