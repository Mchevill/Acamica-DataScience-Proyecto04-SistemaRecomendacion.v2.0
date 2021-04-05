# [Acamica](acamica.com) Proyecto 4
Continuación del [Proyecto 3](https://github.com/Mchevill/Acamica-DataScience-Proyecto03-SistemaRecomendacion) propuesto en el curso de Data Science en Acamica. Desarrollo y optimización de un sistema de recomendación de juegos para usuarios de la plataforma Steam.

El objetivo de este proyecto es desarrollar nuevos modelos para comparar resultados con los obtenidos en el Proyecto 3 y mejorar el tiempo de la optimización de hiperparametros utilizando el método bayesiano desarrollado en este [articulo](https://machinelearningmastery.com/what-is-bayesian-optimization/). la base de datos provista por Steam se puede descargar [aquí](https://github.com/kang205/SASRec). Este proyecto se desarrolló en el leguaje Python y se utilizan las librerías Numpy, Pandas, Matplotlib, Seaborn, Sklearn, scikit-optimize e Implicit.

Este proyecto se divide en 5 partes:
1. Análisis exploratorio del Dataset.
2. Transformaciones para los modelos.
3. Desarrollo de modelos y optimización de hiperparametros.
4. Análisis sobre un usuario aleatorio.
5. Conclusiones.

Los modelos utilizados en este proyecto son **mínimos cuadrados alternantes (ALS)** basado en el [articulo](http://yifanhu.net/PUB/cf.pdf) al igual que en el Proyecto 3 y **K vecinos más cercanos (KNN) utilizando la medida de similitud coseno y similitud BM25**. La métrica, para comparar los modelos, utilizada es **Precisión Media Promedio (MAP)**.

