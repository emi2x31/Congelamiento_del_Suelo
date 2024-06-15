
![Congelamiento del Suelo](https://github.com/emi2x31/Congelamiento_del_Suelo/blob/main/reports/figures/calles%20congeladas2.jpg)

DESCRIPCION DEL CONJUNTO DE DATOS
------------

Origen del Dataset
-----------------
   •	__Centro de Información Meteorológica (CIM).__

   •	__Fuente:__ Servicio Meteorológico Nacional.

   •	__Fecha de Adquisición:__ 3 de junio de 2024.

   •	__Recopilación:__ Los datos fueron enviados por Nadia Cieslinski.

   •	__Política de Datos:__ Comprendidos dentro de la Política de Datos Públicos, por lo que son gratuitos.

   •	__Nota:__ La información básica en el archivo puede sufrir variaciones debido a procesos de consistencia y depuración.

------------
Descripción del Dataset
------------

  • __Cantidad de Instancias:__ El dataset contiene datos horarios de la estación meteorológica Aeropuerto Ushuaia desde el 1 de enero de 2019 hasta el 31 de mayo de 2024.

  •	__Periodo Cubierto:__ 1977 días completos, correspondientes a 5 años y 5 meses.
  
  •	__Frecuencia:__ 24 instancias por día (una por cada hora).

  •	__Total de Instancias:__ 47,448 registros.

------------
Características (Columnas) y Tipos de Datos
-----------

  1.	__Fecha:__ Fecha del registro (tipo: fecha).
  2.	__Hora:__ Hora del registro en formato 24 horas (tipo: entero).
  3.	__Temperatura en °C:__ Temperatura medida en grados Celsius (tipo: float).
  4.	__Humedad Relativa en %:__ Porcentaje de humedad relativa (tipo: entero).
  5.	__Dirección del Viento en Decagrados:__ Dirección del viento medida en decagrados (tipo: entero).
  6.	__Velocidad en km/h:__ Velocidad del viento en kilómetros por hora (tipo: entero).
  7.	__Dirección de Ráfaga en Decagrados:__ Dirección de las ráfagas de viento en decagrados (tipo: entero).
  8.	__Velocidad de Ráfaga en km/h:__ Velocidad de las ráfagas de viento en kilómetros por hora (tipo: entero).
  9.	__Precipitación en mm C/6 hs:__ Precipitación acumulada en milímetros cada 6 horas (tipo: float, con valores nulos cuando no hay precipitación).

-------------
Información Relevante Adicional
------------
  •	__Datos Preliminares:__ Los datos están etiquetados como "Datos Preliminares", lo que sugiere que pueden estar sujetos a cambios después de procesos de consistencia y depuración.

  •	__Valores Faltantes:__ Existen valores faltantes o nulos en algunas columnas, especialmente en las relacionadas con la dirección y velocidad de ráfaga, así como en la precipitación.

----------------

Procesos de Preprocesamiento
----------------

Para preparar este dataset para un proyecto de aprendizaje automático, se podrían considerar los siguientes pasos de preprocesamiento:
  1.	__Manejo de Valores Faltantes:__ Imputar o eliminar registros con valores nulos.
  2.	__Conversión de Tipos de Datos:__ Asegurar que todos los datos están en el formato correcto.
  3.	__Normalización/Estandarización:__ Dependiendo del algoritmo a utilizar, podría ser necesario normalizar o estandarizar los datos.
  4.	__Generación de Nuevas Características:__ Crear características adicionales como promedios móviles o variaciones diarias.
     

  **[⬆ Volver al Indice](https://github.com/emi2x31/Congelamiento_del_Suelo/#Indice)**




-----------
