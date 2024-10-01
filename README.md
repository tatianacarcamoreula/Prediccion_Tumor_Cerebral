# Predicción_Tumor_Cerebral
En el notebook "Prediccion_tumor_cerebral.ipynb", se encuentra el proceso de creación de un modelo de Deep Learning Convolucional con el objetivo de predecir un tumor cerebral dependiendo de la imagen dada.

## Proceso del proyecto
*	Recolección de datos (en este caso, la imagenes de cada clasificación).
* Procesamiento de datos:
  * pasar las imagenes y su clase a un dataframe para entender mejor su distrubución.
  * Verificar que no hayan datos nulos.
  * Verificar cantidad de datos a analizar.
* Exploración de los datos:
  * Visualizar algunas imagenes imagenes.
  * Visualizar la cantidad de imagenes por cada clase.
* Procesamiento de datos:
  * Crear datos de validación.
  * Generar las imagenes para el modelo.
*	Generar red neuronal convolucional.
*	Entrenar el modelo.
*	Validar el modelos.
*	Probar el modelo con alguna imagen de ejemplo.

## Librerías usadas
*	Pandas para manipulación y análisis de datos.
*	Matplotlib y Seaborn para visualización de datos y visualizar el entrenamiento del modelo.
*	Scikit-Learn(Sklearn) para la generación de datos de validación y validar el modelo.
*	Keras y TensorFlow para la generación de imagenes a partir de un dataframe, crear la red neuronal convolucional y entrenar el modelo.

## Link del Dataset usado para el modelo de machine learning
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data
