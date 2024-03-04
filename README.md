# ML_Clasificador_Setas

## Proyecto de ML - ¿Setas comestibles o venenosas?

### Autore
>Thide E. Llorente Llorente, para The Bridge | Digital Talent Accelerator

### Fecha
>04 de marzo de 2024

### Librerías empleadas
>numpy

>pandas

>seaborn

>matplotlib

>plotly

>scikit-learn

>phik

### Recursos utilizados
>Apuntes proporcionados por los profesores Alberto Romero y Antonio de la Macorre

>Tutorías con los citados profesores

>Visual Studio Code

>Stack Overflow para resolución de dudas

>debugging de Python

>Videotutoriales del usuario Codigo Maquina en YouTube

### Datos utilizados
> Dataset obtenido de Kaggle: https://www.kaggle.com/datasets/uciml/mushroom-classification
> Para interpretar las categorías de las variables, recomendamos acudir a la fuente original, 
UCI Machine Learning Repository, en https://archive.ics.uci.edu/dataset/73/mushroom

### Descripción del proyecto

Mi proyecto de Machine learning pretende responder a la siguiente demanda hipotética:

*“El alcalde un pueblo de Castilla y León está preocupado por las continuas intoxicaciones 
que sufren los vecinos del pueblo y, especialmente, los turistas, debido a la ingestión de 
las setas silvestres que recogen del campo. Nos pide que tratemos de identificar las 
características de las setas que, con gran acierto, permitan distinguir una seta venenosa de 
una comestible. Con esas características desea elaborar un folleto que ayude a los 
ciudadanos a identificar adecuadamente los dos tipos de setas, por lo que insiste en que 
seleccionemos únicamente unas pocas de las características más relevantes”.*

Traducido a nuestro trabajo, vamos a seleccionar las features más importantes y a buscar 
un modelo supervisado de clasificación que nos permita lograr un buen recall.

El proyecto ha constado de las siguientes fases:

1) **Análisis exploratorio, limpieza y preprocesado de los datos**. Se puede consultar en el notebook ``1.Preparando_df_y_ft_importance.ipynb``.
2) **Modelado de los datos con Machine Learning**. Se puede consultar en el notebook ``2.Modelado_y_GridSearchCV.ipynb``.
3) **Extra-A: Exploración gráfica de la distribución espacial de los registros**. Se puede consultar en el notebook `` 3.Extra_A_Distribucion_espacial_datos.ipynb``.
4) **Extra-B: Exploración de la magnitud del recall según el número de variables seleccionadas**. Se puede consultar en el notebook ``4.Extra_B_Recall_segun_n_features.ipynb``.
