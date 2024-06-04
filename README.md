

![Congelamiento del Suelo](https://github.com/emi2x31/Congelamiento_del_Suelo/blob/main/reports/figures/calles%20congeladas2.jpg)


Predecir si el suelo está por congelarse en Ushuaia, Tierra del Fuego, Argentina
---------
---------------
Bloque: Aprendizaje Automatico

Alumno: ORTEGA, Emilio

--------------

•	Proporcionar una descripción detallada de su proyecto de Aprendizaje Automático.  Sobre el Tema: Predecir si el suelo está por congelarse.

•	Formular claramente el objetivo del trabajo, indicando qué problema específico de su interés abordará con el modelo.

•	Proporcionar detalles sobre el contexto en el que se encuentra el problema y por qué es relevante.

•	Defina claramente las preguntas de investigación o hipótesis que desea responder a través del aprendizaje automático.

-----------
Descripción y Formulación del Objetivo
------------
Tema: Predecir si el suelo está por congelarse
------------

Objetivo del Proyecto:
-------------
El objetivo principal de este proyecto es desarrollar un modelo de aprendizaje automático capaz de predecir si el suelo está por congelarse en una ubicación específica. Este modelo será entrenado utilizando datos históricos de variables meteorológicas y condiciones del suelo para identificar patrones y características asociadas con el congelamiento del suelo.

------------

Contexto y Relevancia:
-----------
El congelamiento del suelo es un fenómeno climático que puede tener impactos significativos en diversas industrias y sectores, incluyendo la agricultura, la construcción, el transporte y la seguridad pública. Poder predecir con anticipación cuándo es probable que ocurra el congelamiento del suelo puede permitir a las organizaciones y autoridades tomar medidas preventivas y preparativas, mitigando así los posibles efectos negativos.

------------

Preguntas de Investigación:
-----------
1. ¿Cuáles son las variables meteorológicas más relevantes para predecir el congelamiento del suelo?
2. ¿Qué características del suelo influyen en su propensión al congelamiento?
3. ¿Existen patrones estacionales o temporales en la ocurrencia del congelamiento del suelo?
4. ¿Qué tipo de modelo de aprendizaje automático es más adecuado para este problema?
5. ¿Cómo se pueden obtener y preprocesar los datos necesarios para entrenar el modelo de manera efectiva?

Estas preguntas de investigación guiarán el desarrollo del proyecto de aprendizaje automático y ayudarán a identificar los factores clave que influyen en el congelamiento del suelo, así como la mejor manera de abordar el problema utilizando técnicas de aprendizaje automático.

------------
Metodología:
-----------

El proyecto seguirá los siguientes pasos:
1. Recopilación de Datos: Se recopilarán datos históricos de variables meteorológicas (como temperatura, humedad, precipitación, etc.) y características del suelo de una o varias ubicaciones relevantes.
2. Preprocesamiento de Datos: Se realizará un proceso de limpieza y preparación de los datos para eliminar valores atípicos, manejar datos faltantes y convertir los datos en un formato adecuado para el entrenamiento del modelo.
3. Selección de Características: Se identificarán las características más relevantes para la predicción del congelamiento del suelo utilizando técnicas de selección de características.
4. Entrenamiento del Modelo: Se entrenarán varios modelos de aprendizaje automático, como modelos de regresión, clasificación o métodos basados en árboles de decisión, utilizando los datos preparados.
5. Evaluación del Modelo: Se evaluará el rendimiento de los modelos utilizando métricas adecuadas, como precisión, sensibilidad y especificidad, utilizando conjuntos de datos de prueba.
6. Optimización y Ajuste del Modelo: Se realizarán ajustes en los hiperparámetros y la arquitectura del modelo para mejorar su rendimiento.
7. Despliegue y Monitoreo: Una vez que se haya seleccionado el modelo final, se implementará en un entorno de producción y se monitoreará su rendimiento continuamente para realizar ajustes según sea necesario.
   
Conclusiones Esperadas:
Se espera que este proyecto proporcione un modelo de aprendizaje automático efectivo y preciso para predecir el congelamiento del suelo, lo que podría tener importantes implicaciones en la planificación y toma de decisiones en una variedad de sectores. Además, se espera que este proyecto contribuya al conocimiento científico sobre los factores que influyen en el congelamiento del suelo y su predicción.


------------
Organizacion del Proyecto
------------

├── LICENSE
├── Makefile           <- Makefile con comandos como `make data` o `make train`
├── README.md          <- El README del nivel superior para desarrolladores o usuarios de este proyecto.
├── data
│   ├── external       <- Datos de fuentes externas.
│   ├── interim        <- Datos intermedios que han sido transformados.
│   ├── processed      <- Datasets finales para el modelado.
│   └── raw            <- Datos crudos internos.
│
├── docs               <- Un proyecto Sphinx por defecto, vea sphinx-doc.org para mas detalles.
│
├── models             <- Modelos entrenados, predicciones o resumenes de modelos.
│
├── notebooks          <- Jupyter notebooks. La convencion para            		nombrarlos es un
│                                    numero (para ordenarlos) seguido de las iniciales del creador y una descripcion corta 
│                                   demilitada por "-" por ejemplo `1.0-jqp-exploracion-inicial-datos`.
│
├── references         <- Diccionario de datos, manuales y otro material explicativo.
│
├── reports            <- Analisis generado como HTML, PDF, LaTeX, etc.
│   └── figures        <- Graficos y figuras generadas para ser usadas en reportes.
│
├── requirements.txt   <- El archivo de requerimientos para reproducir el ambiente de analisis por ejemplo
│                         generado con `pip freeze > requirements.txt`
│
├── setup.py           <- hace el proyecto instalable mediante pip  (pip install -e .) asi src puede ser importado. can be imported
├── src                <- Codigo fuente usado en este proyecto.
│   ├── __init__.py    <- Hace a src un modulo de Python
│   │
│   ├── data           <- Scripts para descargar o generar los datos.
│   │   └── make_dataset.py
│   │
│   ├── features       <- Scripts para transformar los datos crudos en features para el modelado.
│   │   └── build_features.py
│   │
│   ├── models         <- Scripts para entrenar modelos y luego hacer predicciones.
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualization  <- Scripts para crear visualizaciones orientadas a la exploracion de datos o a los resultados.
│       └── visualize.py
│
└── tox.ini            <- archvi tox con ajustes para ejecutar tox; vea tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
