# Reconocimiento de Frutas con CNN

## Objetivos: 

A partir de nuestra base de datos, un conjuntos de distintos tipos de frutas, se busca entrenar el modelo de CNN y aplicar las medidas de evaluación para verificar cómo el modelo obtiene predicciones. 

Usaremos las siguientes medidas de evaluación para evaluar el desempeño del modelo: 
- Precisión 
- Gráficas de puntajes de entrenamiento y validación


## Herramienta
> - Google Colab
> - Token de su cuenta de Kaggle

## Base de Datos

- Se utilizó el de Fruits-360 de [Kaggle](https://www.kaggle.com/moltean/fruits)


## Exploración de Datos

>- Total de números de imágenes: 12455 imagenes en RGB
>- Conjunto de datos de Entrenamiento: 6231 imágenes
>- Conjunto de datos de Validación: 3114 imágenes
>- Conjunto de datos de Test: 3110 imágenes
>- Cantidad de clases: 24 tipos de frutas.


## Procesamiento de Datos
> Limpieza de Datos:
> Convertimos las etiquetas de Entrenamiento y de Prueba en One-Hot
> Dividir el conjunto de validación en el conjunto de prueba y el de la validación

## Procesamiento de Imágenes
> Data Augmentation

## Redes Neuronales Convolucionales

