![Congelamiento del Suelo](https://github.com/emi2x31/Congelamiento_del_Suelo/blob/main/reports/figures/calles%20congeladas2.jpg)


CONGELAMIENTO DEL SUELO - USHUAIA-TIERRA DEL FUEGO - ARGENTINA
---------
---------------
Bloque: Aprendizaje Automatico

Autor: ORTEGA, Emilio

--------------


💡

# Indice

- [Informe del Proyecto](#Informe)
- [Objetivo del Proyecto](#Objetivo)
- [Contexto y Relevancia](#Contexto)
- [Preguntas de Investigación](#Preguntas)
- [Metodología](#Metodología)
- [Conclusiones Esperadas](#Conclusiones)
- [Dataset Utilizados](https://github.com/emi2x31/Congelamiento_del_Suelo/tree/main/data/external)
- [Descripción sobre origen y tipo de datos](./docs/Descripcion%20de%20los%20Datos.md)
- [Notebook del trabajo final](./notebooks/Version3_PredecirCongelamientodelSuelo.ipynb)
- [Modelo y Analisis de Resultados](./reports/Reporte%20de%20Resultados.md)





-------------
# Informe:

Este informe presenta un modelo de aprendizaje automático diseñado para predecir la congelación de las rutas en ubicaciones específicas. Se recopilaron y preprocesaron datos históricos sobre variables meteorológicas y condiciones de las rutas para identificar patrones asociados con el congelamiento de las mismas. Se aplicaron técnicas de selección de características para identificar predictores relevantes, los cuales fueron utilizados para entrenar y evaluar varios algoritmos de aprendizaje automático, incluidos métodos de regresión y árboles de decisión. El rendimiento de estos algoritmos se evaluó utilizando métricas como precisión, sensibilidad y especificidad. El modelo seleccionado se optimizó para mejorar su rendimiento y se desplegó para monitoreo y ajuste en tiempo real. Los resultados demuestran la efectividad del modelo en predecir la formación de hielo en las rutas, proporcionando conocimientos valiosos para la toma de decisiones en diversos sectores, como la seguridad vial y la construcción. Esta investigación contribuye a comprender los factores que influyen en el congelamiento de las rutas y mejora las capacidades predictivas en campos relacionados.

**[⬆ Volver al Indice](#Indice)**



-------------
# Objetivo:

El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático capaz de predecir si el suelo está por congelarse en una ubicación específica. Este modelo será entrenado utilizando datos históricos de variables meteorológicas y condiciones del suelo para identificar patrones y características asociadas con el congelamiento del suelo.


**[⬆ Volver al Indice](#Indice)**



----------------
# Contexto:

El congelamiento del suelo es un fenómeno climático que puede tener impactos significativos en diversas industrias y sectores, incluyendo la agricultura, la construcción, el transporte y la seguridad pública. Poder predecir con anticipación cuándo es probable que ocurra el congelamiento del suelo puede permitir a las organizaciones y autoridades tomar medidas preventivas y preparativas, mitigando así los posibles efectos negativos.


**[⬆ Volver al Indice](#Indice)**



------------
# Preguntas:

1. ¿Cuáles son las variables meteorológicas más relevantes para predecir el congelamiento del suelo?
2. ¿Qué características del suelo influyen en su propensión al congelamiento?
3. ¿Existen patrones estacionales o temporales en la ocurrencia del congelamiento del suelo?
4. ¿Qué tipo de modelo de aprendizaje automático es más adecuado para este problema?
5. ¿Cómo se pueden obtener y preprocesar los datos necesarios para entrenar el modelo de manera efectiva?

Estas preguntas de investigación guiarán el desarrollo del proyecto de aprendizaje automático y ayudarán a identificar los factores clave que influyen en el congelamiento del suelo, así como la mejor manera de abordar el problema utilizando técnicas de aprendizaje automático.

Las respuestas a estas preguntas se pueden encontrar al final del notebook presentado siga el link  ==> [Notebook del trabajo final](./notebooks/Version3_PredecirCongelamientodelSuelo.ipynb)


**[⬆ Volver al Indice](#Indice)**



----------------
# Metodología:

El proyecto seguirá los siguientes pasos:
1. Recopilación de Datos: Se recopilarán datos históricos de variables meteorológicas (como temperatura, humedad, precipitación, etc.) y características del suelo de una o varias ubicaciones relevantes.
2. Preprocesamiento de Datos: Se realizará un proceso de limpieza y preparación de los datos para eliminar valores atípicos, manejar datos faltantes y convertir los datos en un formato adecuado para el entrenamiento del modelo.
3. Selección de Características: Se identificarán las características más relevantes para la predicción del congelamiento del suelo utilizando técnicas de selección de características.
4. Entrenamiento del Modelo: Se entrenarán varios modelos de aprendizaje automático, como modelos de regresión, clasificación o métodos basados en árboles de decisión, utilizando los datos preparados.
5. Evaluación del Modelo: Se evaluará el rendimiento de los modelos utilizando métricas adecuadas, como precisión, sensibilidad y especificidad, utilizando conjuntos de datos de prueba.
6. Optimización y Ajuste del Modelo: Se realizarán ajustes en los hiperparámetros y la arquitectura del modelo para mejorar su rendimiento.
7. Despliegue y Monitoreo: Una vez que se haya seleccionado el modelo final, se implementará en un entorno de producción y se monitoreará su rendimiento continuamente para realizar ajustes según sea necesario.

**[⬆ Volver al Indice](#Indice)**



-----------------------
# Conclusiones:

Se espera que este proyecto proporcione un modelo de aprendizaje automático efectivo y preciso para predecir el congelamiento del suelo, lo que podría tener importantes implicaciones en la planificación y toma de decisiones en una variedad de sectores. Además, se espera que este proyecto contribuya al conocimiento científico sobre los factores que influyen en el congelamiento del suelo y su predicción.

Las conclusiones obtenidas se pueden encontrar en el siguiente link ==> [Modelo y Analisis de Resultados](./reports/Reporte%20de%20Resultados.md)


**[⬆ Volver al Indice](#Indice)**




------------
Project Structure

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train` 
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
