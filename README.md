# prediccion_calidad_de_vinos
Análisis integral de los datos de calidad de vinos
Propósito del Proyecto
Este proyecto tiene como objetivo predecir el precio de vehículos usados utilizando técnicas de Machine Learning. El conjunto de datos utilizado contiene información sobre características de vehículos como año, kilometraje, fabricante, tipo de combustible, estado del título y transmisión. El objetivo es limpiar, preprocesar y modelar estos datos para crear un predictor preciso que pueda ser utilizado en el mercado de vehículos usados.

Técnicas Utilizadas
Limpieza y Preprocesamiento de Datos:

Eliminación de duplicados utilizando el número de identificación del vehículo (VIN).

Filtrado de filas con precios igual a cero.

Eliminación de columnas irrelevantes para el modelo.

Imputación de valores faltantes utilizando medianas y modas agrupadas por características relevantes.

Tratamiento de outliers para mejorar la calidad de los datos.

Análisis Exploratorio de Datos (EDA):

Visualización de la distribución de precios y otras variables numéricas.

Creación de nuevas variables derivadas como la edad del vehículo y millas por año.

Feature Engineering:

Transformación de variables categóricas en numéricas mediante técnicas como One-Hot Encoding.

Normalización de variables numéricas para mejorar el rendimiento del modelo.

Modelado:

División del conjunto de datos en entrenamiento y prueba.

Implementación de algoritmos de regresión como Random Forest, Gradient Boosting y Regresión Lineal.

Evaluación del rendimiento utilizando métricas como RMSE y R².

Cómo Ejecutar el Código
Requisitos:

Python 3.7 o superior.

Bibliotecas necesarias: pandas, numpy, matplotlib, seaborn, scikit-learn.

Instalar las dependencias con: pip install pandas numpy matplotlib seaborn scikit-learn.

Pasos para Ejecución:

Clona el repositorio: git clone [URL del repositorio].

Navega al directorio del proyecto: cd [nombre del repositorio].

Ejecuta el notebook Jupyter: jupyter notebook Predicción_de_Precios_de_Vehículos_Usados_(Core).ipynb.

Sigue las instrucciones dentro del notebook para cargar los datos, preprocesarlos y entrenar los modelos.

Datos:

El conjunto de datos original se encuentra en formato Parquet y debe estar ubicado en la ruta especificada en el notebook. Asegúrate de ajustar la ruta según tu entorno.

Estructura del Repositorio
Predicción_de_Precios_de_Vehículos_Usados_(Core).ipynb: Notebook principal con el código completo.

README.md: Este archivo con la documentación del proyecto.

data/: Directorio para almacenar el conjunto de datos (no incluido en el repositorio por defecto).
