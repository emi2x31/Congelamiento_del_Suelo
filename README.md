### Determinación de Voto Migratorio
![](https://cdn-icons-png.flaticon.com/256/3669/3669035.png)

El presente **trabajo de Aprendizaje Automático **pretende formular un modelo que permita **determinar la presencia del voto migratorio** a instancias de un set de datos generado por una encuesta de investigación electoral. 
A tales efectos es importante señalar que el set de datos original que fue producto de un proceso de investigación factico, fue recortado extrayendo del mismo 3 variables que resultan fundamentales para el avance del objeto de estudio en cuestión.
Por otro lado, cabe destacar que en términos de la investigación cuantitativa electoral vinculada a la realización de encuestas, se obtienen datos que en la gran mayoría de los casos responden a la frecuencia del fenómeno observado, pero pocas veces se formula la apreciación intrínseca del comportamiento de los encuestados en tanto electores y sus eventuales comportamientos como el fenómeno de potencial migración de los mismos.
Es en este sentido en el cual radica la importancia de la formulación de un modelo que logre clasificar adecuadamente este fenómeno de comportamiento electoral.
Claramente la búsqueda del modelo estará estrictamente orientada a indagar respecto de la existencia o no de electores que presenten señales de migración electoral, a tales efectos se desarrollara una lógica de carácter selectiva a los efectos de etiquetar adecuadamente aquellos electores que presenten estas individualidades o comportamientos y distinguirlos de aquellos que no las presentan.


Finalmente cuantificar la dimensión en términos de la presencia de este fenómeno dentro del set de datos en cuestión.

Por último, creo que es importante destacar que este proceso de investigación contrastado con otros de similares características a instancias de posteriores ejecuciones en una línea de tiempo progresiva con nuevos set de datos que contengan las mismas variables de observación brindaran una información muy relevante respecto de la progresión del fenómeno observado, lo que ayudara a la determinación de diagnósticos más precisos que se adapten a la coyuntura observada.

------------


A continuación, y a efectos de ser aún más explícitos, pese al desarrollo previo vamos a tipificar y enumerar las preguntas vinculadas al proyecto de investigación propuesto: 
- **1 **¿Es posible desarrollar un modelo que permita determinar la presencia del voto migratorio?
- **2**¿Cómo se puede clasificar adecuadamente el comportamiento electoral de los encuestados?
- **3 **¿Cuál es la dimensión de este fenómeno en el conjunto de datos evaluado?
- **4**¿Cómo se puede contrastar este proceso con ejecuciones posteriores para realizar diagnósticos más precisos?


votomigratorio
==============================

determinar la presencia del voto migratorio

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
