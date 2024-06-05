
## DESCRIPCION DEL CONJUNTO DE DATOS
------------
Descripción del Dataset
------------
------------
Cantidad de Instancias: El dataset contiene datos horarios de la estación meteorológica Aeropuerto Ushuaia desde el 1 de enero de 2019 hasta el 31 de mayo de 2024.
•	Periodo Cubierto: 1977 días completos, correspondientes a 5 años y 5 meses.
•	Frecuencia: 24 instancias por día (una por cada hora).
•	Total de Instancias: 47,448 registros.

------------
Características (Columnas) y Tipos de Datos
-----------

1.	Fecha: Fecha del registro (tipo: fecha).
2.	Hora: Hora del registro en formato 24 horas (tipo: entero).
3.	Temperatura en °C: Temperatura medida en grados Celsius (tipo: float).
4.	Humedad Relativa en %: Porcentaje de humedad relativa (tipo: entero).
5.	Dirección del Viento en Decagrados: Dirección del viento medida en decagrados (tipo: entero).
6.	Velocidad en km/h: Velocidad del viento en kilómetros por hora (tipo: entero).
7.	Dirección de Ráfaga en Decagrados: Dirección de las ráfagas de viento en decagrados (tipo: entero).
8.	Velocidad de Ráfaga en km/h: Velocidad de las ráfagas de viento en kilómetros por hora (tipo: entero).
9.	Precipitación en mm C/6 hs: Precipitación acumulada en milímetros cada 6 horas (tipo: float, con valores nulos cuando no hay precipitación).

-------------
Información Relevante Adicional
------------

•	Datos Preliminares: Los datos están etiquetados como "Datos Preliminares", lo que sugiere que pueden estar sujetos a cambios después de procesos de consistencia y depuración.
•	Valores Faltantes: Existen valores faltantes o nulos en algunas columnas, especialmente en las relacionadas con la dirección y velocidad de ráfaga, así como en la precipitación.
Origen del Dataset
•	Centro de Información Meteorológica (CIM).
•	Fuente: Servicio Meteorológico Nacional.
•	Fecha de Adquisición: 3 de junio de 2024.
•	Recopilación: Los datos fueron enviados por Nadia Cieslinski.
•	Política de Datos: Comprendidos dentro de la Política de Datos Públicos, por lo que son gratuitos.
•	Nota: La información básica en el archivo puede sufrir variaciones debido a procesos de consistencia y depuración.

-----------------
Procesos de Preprocesamiento
----------------

Para preparar este dataset para un proyecto de aprendizaje automático, se podrían considerar los siguientes pasos de preprocesamiento:
1.	Manejo de Valores Faltantes: Imputar o eliminar registros con valores nulos.
2.	Conversión de Tipos de Datos: Asegurar que todos los datos están en el formato correcto.

-----------
