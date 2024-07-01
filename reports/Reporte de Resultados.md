![Presentacion_del_modelo](https://github.com/emi2x31/Congelamiento_del_Suelo/blob/main/reports/figures/analisis_de_resulatdos1.png)


1.	Presentar  modelo de Aprendizaje Automático y los resultados obtenidos.
2.	Describa los orígenes de datos nuevamente para recordar a la audiencia.
3.	Proporcione un análisis exploratorio de datos que incluya gráficos y estadísticas relevantes.
4.	Presente las conclusiones clave derivadas del análisis exploratorio.
5.	Detalle el modelo de Aprendizaje Automático que ha desarrollado, incluyendo la arquitectura, algoritmos utilizados, y cualquier ajuste de hiperparámetros.
6.	Proporcione métricas de evaluación del modelo, como precisión, recall, F1-score, y cualquier otra métrica relevante.
7.	Interprete los resultados del modelo y ofrezca conclusiones finales sobre cómo su modelo abordó el problema formulado en la primera entrega.



1  Presentar el modelo de Aprendizaje Automático y los resultados obtenidos
---------------

El modelo desarrollado es un RandomForestClassifier, el cual es un algoritmo de aprendizaje supervisado utilizado para clasificación. Este modelo fue entrenado con los datos de características como temperatura, humedad relativa, precipitación, entre otras. Los resultados del modelo muestran una precisión adecuada para predecir si el suelo está congelado o no.


2  Describir los orígenes de datos
-----------------

Los datos utilizados provienen de un archivo de Excel llamado `USHUAIAAERO.xlsx`, el cual contiene información meteorológica diaria de Ushuaia. Las columnas incluyen medidas como la temperatura en grados Celsius, la humedad relativa y la precipitación en milímetros. Estos datos fueron utilizados para calcular varias características adicionales, como la temperatura mínima en una ventana de tres días, los días consecutivos bajo cero y los eventos de heladas.


3  Análisis exploratorio de datos (EDA)
--------------

El análisis exploratorio de datos incluyó la generación de estadísticas descriptivas y varios gráficos. Las estadísticas descriptivas proporcionaron un resumen de las principales medidas centralizadas y de dispersión. Los gráficos generados incluyen:
- Un gráfico de barras de la importancia de las características, destacando cuáles son las más influyentes para la predicción.
- Un scatter plot comparando las predicciones del modelo con los valores reales.
- Gráficos de barras mostrando la ocurrencia de congelamiento del suelo por mes y por año.


4  Conclusiones clave derivadas del análisis exploratorio
-----------------

Del análisis exploratorio se derivaron varias conclusiones clave:
- La temperatura muestra una alta variabilidad diaria.
- La mayoría de los eventos de suelo congelado ocurren durante los meses de invierno, como se observó en la distribución mensual de los datos.


5  Detalle del modelo de Aprendizaje Automático
-----------------

El modelo utilizado es un RandomForestClassifier con 100 árboles y una semilla aleatoria para reproducibilidad. Este modelo se seleccionó por su capacidad para manejar conjuntos de datos con múltiples características y su eficacia en tareas de clasificación. Se entrenó utilizando las características seleccionadas y se evaluó mediante técnicas de validación cruzada para asegurar su robustez.
Entrenamiento del Modelo
Entrenar el modelo utilizando el conjunto de entrenamiento.

![image](https://github.com/emi2x31/Congelamiento_del_Suelo/assets/143364681/5da16871-c840-479b-92a9-7b92080abc12)
![image](https://github.com/emi2x31/Congelamiento_del_Suelo/assets/143364681/a40325b7-473f-4187-945e-36da62658493)

El RandomForestClassifier utilizado en el entrenamiento emplea múltiples árboles de decisión y utiliza una semilla aleatoria específica (42 en este caso) para garantizar la reproducibilidad de los resultados durante el entrenamiento y la evaluación del modelo.

Validación Cruzada
-----------
Realizar validación cruzada para asegurar que el modelo generaliza bien a datos no vistos

![image](https://github.com/emi2x31/Congelamiento_del_Suelo/assets/143364681/ff667081-d215-4801-9d50-7d6a2cc24c19)

Los resultados de la validación cruzada que se obtuvo indican que el modelo tiene un rendimiento consistente y muy alto en diferentes particiones de los datos de entrenamiento. 
Explicación:
- Cross-validation scores: Estos son los puntajes de precisión obtenidos en cada una de las particiones (folds) durante el proceso de validación cruzada. Cada número representa la precisión del modelo en una partición específica de los datos.
- Mean cross-validation score: Es el promedio de los puntajes de precisión obtenidos en todas las particiones durante la validación cruzada. Este valor proporciona una estimación general del rendimiento esperado del modelo cuando se aplica a datos nuevos y no vistos.
En este caso, el promedio de los puntajes de validación cruzada es aproximadamente 0.99976, lo cual indica que el modelo tiene una alta precisión y generaliza bien a datos que no ha visto durante el entrenamiento. Esto sugiere que el modelo es robusto y efectivo para realizar predicciones precisas sobre si el suelo está congelado o no en condiciones similares a las del conjunto de datos utilizado.


6  Proporcionar métricas de evaluación del modelo
------------------

Las métricas de evaluación incluyeron:
- Precisión (accuracy): La fracción de predicciones correctas sobre el total de predicciones.
- Reporte de clasificación (classification report): Proporciona información detallada sobre la precisión, recall y F1-score para cada clase.
- Matriz de confusión: Muestra los verdaderos positivos, falsos positivos, verdaderos negativos y falsos negativos, proporcionando una visión más detallada de las predicciones del modelo.
Evaluación del Modelo

![image](https://github.com/emi2x31/Congelamiento_del_Suelo/assets/143364681/cb43ffc9-2c15-48b2-9888-b116509e808d)
![image](https://github.com/emi2x31/Congelamiento_del_Suelo/assets/143364681/a97ec8bc-1da4-4feb-bfc7-6d568735368b)


Interpretación de Resultados del Modelo de Aprendizaje Automático
-------------

Precisión del Modelo
Accuracy: 0.9995
  - La precisión del modelo es extremadamente alta, alcanzando casi el 100%. Esto indica que el modelo clasifica correctamente la gran mayoría de los casos, tanto de suelo congelado como no congelado.
Reporte de Clasificación
El reporte de clasificación proporciona detalles sobre las métricas clave para cada clase (suelo congelado y no congelado).
Clase False (suelo no congelado)
  - Precisión: 1.00
    - De todas las predicciones realizadas para suelo no congelado, el 100% fueron correctas.
  - Recall: 1.00
    - De todos los casos reales de suelo no congelado, el 100% fueron identificados correctamente.
  - F1-Score: 1.00
    - La combinación de precisión y recall también es perfecta, indicando un rendimiento excelente.
- Clase True (suelo congelado)
  - Precision: 0.99
    - El 99% de las predicciones realizadas para suelo congelado fueron correctas.
  - Recall: 1.00
    - El modelo identificó correctamente todos los casos reales de suelo congelado.
  - F1-Score: 0.99
    - La combinación de precisión y recall para suelo congelado es muy alta, aunque no perfecta, indicando un rendimiento ligeramente inferior comparado con la clase de suelo no congelado.
 Métricas Agregadas
- Macro Avg (Promedio Macro)
  - Precision: 0.99
  - Recall: 1.00
  - F1-Score: 1.00
  - Estas métricas indican un alto rendimiento generalizado del modelo, equilibrado para ambas clases.
- Weighted Avg (Promedio Ponderado)
  - Precision: 1.00
  - Recall: 1.00
  - F1-Score: 1.00
  - El promedio ponderado toma en cuenta la cantidad de casos en cada clase, reflejando el alto rendimiento del modelo en general.
   

Conclusion
-------------

1. Precisión Excepcional: La precisión del modelo es casi perfecta, lo que sugiere que el modelo es altamente confiable para predecir si el suelo está congelado o no.
2. Desempeño Equilibrado: Aunque el modelo muestra una ligera diferencia en precisión entre las clases, el rendimiento es muy alto para ambas, lo que es crucial en aplicaciones prácticas.
3. Utilidad en la Práctica: Con un recall del 100% para la clase de suelo congelado, el modelo no omite ningún caso de suelo congelado, lo cual es vital para prevenir posibles daños o problemas relacionados con el suelo congelado.
E modelo RandomForestClassifier desarrollado ha demostrado ser extremadamente efectivo para predecir el estado del suelo en términos de congelamiento, lo que lo hace una herramienta valiosa para aplicaciones en el monitoreo y gestión de suelos en climas fríos como Ushuaia.


7  Interpretar los resultados del modelo
---------------

Los resultados del modelo indican una buena precisión general para predecir si el suelo está congelado. La evaluación de la importancia de las características reveló que las características más relevantes son la temperatura mínima, los días consecutivos bajo cero y la humedad relativa. Estas características influyen significativamente en la predicción del suelo congelado, lo cual es consistente con la lógica meteorológica. Las predicciones y evaluaciones sugieren que el modelo es adecuado para abordar el problema de predicción del suelo congelado en Ushuaia.

    
  **[⬆ Volver al Indice](https://github.com/emi2x31/Congelamiento_del_Suelo/#Indice)**




-----------
