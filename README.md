# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>

## **Introducción al proyecto.**
El objetivo de este proyecto es probar y analizar la capacidad de predicción de diferentes modelos de machine learning. Se toma un archivo csv que cuenta con diferentes características de pacientes y el tiempo que estuvieron internados. En consecuencia, la finalidad es poder predecir ante nuevos supuestos si el paciente va estar internado por un lapso mayor a 8 dias o no.

#### **Analisis Exploratorio de Datos (EDA)**

Lo primero que cabe mencionar es que nuestros datos provienen de dos archivos diferentes, uno para entrenamiento y otro para testeo. Estos se encuentran disponibles en la carpeta Datasets.

Lo relativo al analisis exploratorio  lo podemos encontrar en el archivo EDA.ipynb. Se eligió utilizar Jupyter Notebook por que nos permitió hacer el analisis mas sencillo y segmentado.
El primer paso fue ingestar los achivos en diferentes dataframes, analizarlos por separado y luego aplicando los cambios necesarios se concatenaron en un mismo dataframe.

Luego de ello, se analizaron duplicados, valores faltantes, se buscaron errores de carga y en los tipos de los datos.

#### **Extracción y transformación de los datos y prueba de modelos de ML..**
Esta etapa es realizada por dos archivos la primera con un contenido de carácter experimental en el archivo "Transformación y prueba de modelos. ipnb" y la segunda, claramente superadora, cuando se lo hace por medio de la libreria pipeline.
Entonces, el proceso de extración y transformación lo encontramos en la carpeta  Modelos de ML y en el archivo "transformación y prueba de modelos". Si bien se prentendió crear un archivo exclusivo para la normalizacion y luego probar en otro diferente el rendimiento de los modelos, esta idea se abandono porque la forma de presentar los datos afectaba los resultados y por lo tanto no existía una sola y adecuada manera de hacerlo.
En consecuencia, vamos a encontrar en el mismo archivo diferentes transformaciones de los datos y la prueba de los mismos en los diferentes modelos. En cuanto a lo que respecta a ML se uso la libreria SKlearn, principalmente los modelos de "DecisionTreeClassifier", "KNeighborsClassifier" y "RandomForestClassifier", herraientas como "train_test_split" y "GridSearchCV" para ajustar hiperparametros y "confusion_matrix", "accuracy_score" y "classification_report" para analizar el rendimiento de los modelos.

#### **Creacion de pipeline**
Por último, y con el fin de automatizar y simplificar los procesos se ultilizó la librería pipelines. Asi se logro realizar las tareas de transformación de datos y entrenamiento de los modelos de una manera muy sencilla, práctica y fácilmente reutilizable. Este proceso lo encontramos en el archivo main.ipynb.

## **Herramientas utilizadas.**

* Vs Code.
* Python( pandas, numpy, Sklearn, pipelines).
* Jupyter Notebook.


