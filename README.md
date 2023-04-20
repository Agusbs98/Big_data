# Proyecto final de la asignatura Minería de datos y el paradigma Big Data - curso 2022/23

# Datos utilizados para la obtención de resultados
Para el análisis de datos hemos usado un dataset que contiene información de los vuelos encontrados en Expedia entre las fechas 16/04/2022 y 05/10/2022.
Link a la página fr kaggle del dataset [aquí](https://www.kaggle.com/datasets/dilwong/flightprices).
El dataset ofrece gran variedad de datos acerca de cada vuelo pero para sacar conclusiones interesantes nos hemos enfocado en los siguientes:

- searchDate (Fecha de la búsqueda del vuelo)
- flightDate (Fecha de vuelo)
- startingAirport (Aeropuerto origen)
- destinationAirport (Aeropuerto destino)
- travelDuration (Duración del viaje en horas y minutos)
- isBasicEconomy (Booleano que indica que el precio del vuelo es asequible)
- seatsRemaining (Número de asientos libres en los vuelos)
- totalFare (Precio del vuelo con impuestos añadidos)
- totalTravelDistance (Distancia recorrida en el vuelo contando escalas)
- segmentsAirlineName (Nombre de la aerolínea encargada del vuelo)
- segmentsAirlineCode (Código de la aerolínea encargada del vuelo)

# Resultados gracias a los datos obtenidos 

- Promedio de tarifas por empresa
- Relación entre casos de covid y el número de vuelos
- Número de vuelos por día
- Relación entre distancia y tarifa
- Número de vuelos por aerolínea
- Evolución de la tarifa según los días
- Número de viajes sin escalas
- Vuelos por día
- Viajes más comunes

# Herramientas utilizadas
- Apache Spark: Motor multi-lenguaje utilizado para facilitarnos la ejecución de los datos.
- Python: Lenguaje de programación base para ejecutar spark.
- Github: Servicio online para alojar todo el material correspondiente al proyecto.
- Kaggle: Página web para la obtrención del dataset
