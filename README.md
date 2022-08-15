# Feature Engineering (Kaggle)
En este curso se profundiza sobre uno de los pasos más importantes en el camino hacia la construcción de un gran modelo de aprendizaje automático: la ingeniería de características o **feature engineering**. Se mostrará como:

- Determinar qué características son las más importantes con **[Mutual information](mutual_information_notes.ipynb)**
- Inventar nuevas características utilizando conocimentos del mundo real (**[Feature creation](creating_features_notes.ipynb)**)
- Crear características de segmentación con **[K-Means clustering](kmeans_clustering_notes.ipynb)**
- Descomponer la variación de un conjunto de datos en características con **[Principal Component Analysis](principal_component_analysis.ipynb)**
- Codificar categorías de alta cardinalidad con **[Target Encoding](target_encoding_notes.ipynb)**

El objetivo de la ingeniería de características o **feature engineering** es simplemente hacer que los datos se adapten mejor al problema en cuestión.

Consideremos algunas métricas de temperatura aparente, como lo son el índice de calor o la sensación térmica. Estas cantidades intentan medir la temperatura percibida por los seres humanos basándose en la temperatura del aire, la humedad y la velocidad del viento, cosas que podemos medir directamente. Se puede considerar que la temperatura aparente es el resultado de una especie de **feature engineering**, un intento de hacer que los datos observados sean más relevantes para lo que realmente nos importa: como se siente la temperatura realmente.

Se puede utilizar feature engineering para:
- Mejorar el rendimiento predictivo de un modelo
- Reducir el costo computacional
- Mejorar la interpretabilidad de los resultados.