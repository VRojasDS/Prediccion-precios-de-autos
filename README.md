# Predicción de Precios de Autos

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo de *Machine Learning* capaz de predecir el precio de venta de un automóvil a partir de sus características técnicas y comerciales. El enfoque está orientado al análisis de datos y a la construcción de modelos de regresión que permitan estimar el valor de mercado de un vehículo de forma objetiva.

## Objetivos

* Analizar un conjunto de datos de ventas de automóviles.
* Entrenar y evaluar modelos de regresión.
* Identificar las variables que más influyen en el precio de venta.
* Construir un modelo reproducible y fácil de utilizar.

## Conjunto de Datos

El dataset contiene información histórica de automóviles usados. Las variables incluidas son:

* **Car_Name**: Nombre del modelo del automóvil
* **Year**: Año de fabricación
* **Selling_Price**: Precio de venta (variable objetivo)
* **Present_Price**: Precio actual de mercado del automóvil
* **Kms_Driven**: Kilómetros recorridos
* **Fuel_Type**: Tipo de combustible
* **Seller_Type**: Tipo de vendedor (particular o concesionario)
* **Transmission**: Tipo de transmisión (manual o automática)
* **Owner**: Número de dueños anteriores

## Metodología

1. **Preprocesamiento de Datos**

   * Limpieza y validación de datos
   * Codificación de variables categóricas
   * Escalado de variables numéricas

2. **Análisis Exploratorio de Datos (EDA)**

   * Distribución de precios
   * Relación entre precio y antigüedad
   * Impacto del kilometraje y tipo de combustible

3. **Entrenamiento del Modelo**

   * División del dataset en entrenamiento y prueba
   * Modelos de regresión RandomForestRegressor

4. **Evaluación del Modelo**

   * R2= 96%

## Tecnologías Utilizadas

* Python 
* NumPy
* Pandas
* Scikit-learn
* Joblib
* Seaborn
* Matplotlib
