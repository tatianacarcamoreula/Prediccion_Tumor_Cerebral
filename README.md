# Predicción_Tumor_Cerebral
En el notebook "Prediccion_tumor_cerebral.ipynb", se encuentra el proceso de creación de un modelo de Deep Learning Convolucional con el objetivo de predecir un tumor cerebral a partir de la imagen de una resonancia magnética del cerebro.

## Proceso del proyecto
*	Recolección de datos (en este caso, las imágenes de cada clasificación).
* Procesamiento de datos:
  * Pasar las imágenes y su clase a un dataframe para entender mejor su distribución.
  * Verificar que no haya datos nulos.
  * Verificar cantidad de datos a analizar.
* Exploración de los datos:
  * Visualizar algunas imágenes.
  * Visualizar la cantidad de imágenes por cada clase.
* Procesamiento de datos:
  * Crear datos de validación.
  * Generar las imágenes para el modelo.
*	Generar red neuronal convolucional.
*	Entrenar el modelo.
*	Validar el modelo.
*	Probar el modelo con alguna imagen de ejemplo.

## Librerías usadas
*	Pandas para manipulación y análisis de datos.
*	Matplotlib y Seaborn para visualización de datos y visualizar el entrenamiento del modelo.
*	PIL(Python Imaging Library) para leer imágenes.
*	Scikit-Learn(Sklearn) para la generación de datos de validación y validar el modelo.
*	Keras y TensorFlow para la generación de imágenes a partir de un dataframe, crear la red neuronal convolucional y entrenar el modelo.

## Link del Dataset usado para el modelo de machine learning
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data
