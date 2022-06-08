# Análisis de las empresas zombis colombianas mediante machine learning
Este trabajo de investigación consiste en un análisis al detalle de las características que describen las empresas zombis que residen en Colombia. En análisis se realiza mediante técnicas de aprendizaje automático, que permiten explorar los modelos generados para obtener conocimiento acerca de las empresas zombis.

El trabajo consta de un conjunto de ficheros .ipynb, ordenados secuencialmente, que contienen anotaciones y código que describe todo el trabajo realizado, así como las conclusiones del proyecto.

Se puede encontrar un resumen del trabajo, así como las conclusiones de éste en el [siguiente cuaderno](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%200.%20Resumen.ipynb)

## Dataset
El Dataset de las empresas está facilitado por Santiago Rojo. Consiste en una mezcla de:

* Datos básicos de las empresas (volumen de empleados, localización, fecha de fundación...)
* Datos financieros de los ejercicios 2017-2019.

Los datos son anónimos y no permiten identificar las empresas de origen a las que pertenecen.

## Proceso
El proceso de análisis consta de varias fases, que tienen el objetivo de extraer conocimiento de un conjunto de datos:

1. Análisis de los datos preliminar. Estadística básica y enriquecimiento de datos.
2. Limpieza de datos: tratar los valores erróneos y los outliers.
3. Transformación de datos: creación de nuevas variables financieras clave para describir mejor las empresas.
4. Etiquetado de empresas como Zombis/No zombis. Múltiples criterios puestos a prueba.
5. Creación de modelos de machine learning y extracción de características

Los cuadernos que incluyen todo el trabajo realizado en este proceso son los siguientes:

1. [Análisis, limpieza y transformación de datos básicos](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%201.%20Preprocesamiento%20de%20datos%20basicos.ipynb)
2. [Extracciones de datos](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%202.%20Extracciones.ipynb)
3. [Análisis, limpieza y transformación de datos financieros](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%203.%20Preprocesamiento%20de%20datos%20fiscales.ipynb)
4. [Etiquetado de empresas](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%204.%20Etiquetado%20de%20empresas.ipynb)
5. [Creación de modelos de machine learning](https://github.com/Jolicost/ZombisColombia/blob/main/Apartado%205.%20Modelos.ipynb)

## Machine learning
Para describir las características más relevantes que separan las empresas zombis de las no zombis, se crean varios modelos de aprendizaje automático con el objetivo de clasificar una empresa como zombi o no.

Luego, se utilizan técnicas de **model explainability** para averiguar qué características de las empresas son más influyentes para ser clasificada como zombi.

Los algoritmos de machine learning utilizados son los siguientes:

* Decision Tree
* Logistic regression
* SVM
* Neural Network
* Bagging+Boosting

## Agradecimientos
A Santiago Rojo por todos sus consejos.
