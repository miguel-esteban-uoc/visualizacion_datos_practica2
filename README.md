# Visualizacion datos Practica2

Este repositorio contiene el dataset con el que se ha realizado la presentación (https://public.flourish.studio/story/1807352/) para la práctica II de la asignatura de Visualización de Datos del Master en Ciencia de Datos de la UOC

El dataset está basado en el dataset original

https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data


Se han añadido información derivada. A partir del precio se ha añadido una clasificación categorica. Se ha hecho lo mismo con la aútonomia eléctrica de los vehículos. Por otra parte se han separado en dos campos, logitud y latitud los valores de la posición geográfica de los vehículos.

## Ficha técnica

Número de registros : 112634

### Campos

- `VIN (1-10)`: Valores únicos 7548. Son los 10 primeros valores del número de serie que se otorgan a un modelo determinado.
- `County`: Valores únicos 165. Condado del Estado de Estados Unidos donde se encuentra el vehículo.
- `City`: Valores únicos 629. Ciudad donde se encuentra el vehículo.
- `State`: Valores únicos 45. Estado de Estados Unidos donde se encuentra el vehículo.
- `Postal Code`: Valores únicos 773. Código postal.
- `Model Year`: Valores únicos 20. Año de fabricación del vehículo.
- `Make`: Valores únicos 34. Fabricante .
- `Model`: Valores únicos 115. Módelo del vehículo.
- `Electric Vehicle Type`: Valores únicos 2. Si es un vehículo a baterías o un híbrido enchufable
- `Clean Alternative Fuel Vehicle (CAFV) Eligibility`: Valores únicos 3. Si puede considerarse un alternativa limpia
- `Electric Range`: Valores únicos 101. Autónomia eléctrica.
- `Electric Range Ranked`: Valores únicos 4. Categorías que permiten clasificar el valor de la autonomía eléctrica.
- `Base MSRP`: Valores únicos 30. Precio de venta al público recomendado.
- `Base MSRP Ranked`: Valores únicos 5. Categorías que permiten clasificar el valor del precio.
- `Legislative District`: Valores únicos 50. Distrito legislativo al que pertenece el vehículo.
- `DOL Vehicle ID`: Valores únicos 112634. Mátricula del vehículo
- `Vehicle Location`: Valores únicos 759. Localización geográfica del vehículo.
- `Longitude`: Valores únicos 759. Logitud de la localización geográfica del vehículo.
- `Latitude`: Valores únicos 759. Latitud de la localización geográfica del vehículo.
- `Electric Utility`: Valores únicos 74. Compañia eléctrica a la que está abonada el vehículo.
- `2020 Census Tract`: Valores úncios 2019. Distritos censales del año 2020 al que pertenece el vehículo.


