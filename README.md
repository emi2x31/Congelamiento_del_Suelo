

![Congelamiento del Suelo](https://github.com/emi2x31/Congelamiento_del_Suelo/blob/main/reports/figures/calles%20congeladas.jpg)


Predecir si el suelo está por congelarse en Ushuaia, Tierra del Fuego, Argentina
---------
Bloque: Aprendizaje Automatico
Alumno: ORTEGA, Emilio

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

Project Organization
------------

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
