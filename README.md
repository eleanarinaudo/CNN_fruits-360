<h1  align="center"> Reconocimiento de Frutas con CNN </h1>

## Objetivo

> A partir de nuestra base de datos, un conjuntos de distintos tipos de frutas, se busca entrenar el modelo de CNN y aplicar las medidas de evaluación para verificar cómo el modelo obtiene predicciones. 
> Usaremos las siguientes medidas de evaluación para evaluar el desempeño del modelo: 
>- Precisión 
>- Gráficas de puntajes de entrenamiento y validación

## Herramienta
> - Google Colab
> - Token de la cuenta de Kaggle

## Base de Datos

> Se utilizó el de Fruits-360 de [Kaggle](https://www.kaggle.com/moltean/fruits)


## Exploración y Análisis de Datos

>- Total de números de imágenes: 12455 imagenes en RGB
>- Conjunto de datos de Entrenamiento: 6231 imágenes
>- Conjunto de datos de Validación: 3114 imágenes
>- Conjunto de datos de Test: 3110 imágenes
>- Cantidad de clases: 24 tipos de frutas.
>- Distribución de Frutas con el Conjunto de Entrenamiento
>- Distribución de Frutas con el Conjunto de Prueba

## Procesamiento de Datos
> Cargamos los datos y dividimos el conjunto de datos en entrenamiento y de prueba con nombres de las etiquetas
> Convertimos las etiquetas de Entrenamiento y de Prueba en One-Hot
> Dividir el conjunto de validación en el conjunto de prueba y el de la validación

## Procesamiento de Imágenes
> - Data Augmentation

## Redes Neuronales Convolucionales
> - Modelo Secuencial
> - Conv2D
> - Activation
> - MaxPooling
> - Dropout
> - Flatten
> - Dense

## Compilación de los modelos
> Establecimos la **pérdida**(lost) como `categorical_crossentropy`. La tasa de aprendizaje de la red neuronal para reducir las pérdidas está definida por el **optimizer**. 

## Entrenamiento del modelo con ajuste de parámetros
> - Callbacks
> - Entrenamiento

## Puntuación de precisión en los datos de prueba
> La precisión es el número de imágenes reconocidas correctamente de todas las imágenes

## Visualización de la pérdida y precisión con respecto a las épocas
> Usando el modelo entrenado y obteniendo las predicciones sobre los datos de prueba, realizamos una visualizacion de la perdida y precisión del conjunto de pruebas y de entrenamiento nuestro modelo.

## Predecir los resultados
> Utilizamos imágenes random para verificar si el modelo entrenado obtuvo buenas predicciones sobre los datos de prueba.

# Conclusión
> - Usamos el dataset de Fruits-360 y exploramos los datos de diferentes maneras.
> - Preparamos los datos de las imagenes
> - Entrenamos el modelo basado en **TensorFlow** con todas sus configuraciones.
> - Evaluamos el modelo con precisión y observamos el rendimiento del modelo con gráficos.
> - Trabajamos en el problema de clasificación y específicamente lo llamamos clasificación multiclase porque estamos usando en total 24 clases de frutas.
