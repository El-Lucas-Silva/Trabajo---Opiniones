## ¿Qué es este proyecto?

El código busca entrenar un modelo que logre predecir si una opinión es positiva o negativa, utilizando el procesamiento de lenguaje natural (PLN) y el modelo de Regresión Logística.

> Esto se hizo con ayuda del dataset ***dataset_train_95.csv***

### Columnas del dataset

> **id | autor | declaracion | etiqueta | palabras_clave | tweet | respuesta_mayoria_5_etiquetas	| respuesta_mayoria_3_etiquetas**

# ¿Qué proceso se llevo a cabo?

Se reviso que no existieran datos nulos, para posteriormente, comenzar con el entrenamiento del modelo (el 90% de los datos fueron destinados al entrenamiento)
Además, para el entrenamiento se utilizaron las columnas: palabras_clave, tweet, declaracion y etiqueta.

Luego de entrenar el modelo, se vectorizaron datos y se realizaron predicciones en un dataset sin la columna etiqueta, lo que dio como resultado una precisión del casi 100%

<img width="689" height="83" alt="image" src="https://github.com/user-attachments/assets/2a708d07-bafd-4e24-8b38-176f9c6c3cdb" />

