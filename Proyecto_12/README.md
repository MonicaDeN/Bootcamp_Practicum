# Datos:

1. `DateCrawled` - fecha en la que se descargó el perfil de la base de datos.
2. `Price` - precio en euros.
3. `VehicleType` - tipo de carrocería del vehículo.
4. `RegistrationYear` - año de matriculación del vehículo.
5. `Gearbox` - tipo de caja de cambios.
6. `Power` - potencia del vehículo (caballo de vapor, CV).
7. `Model` - modelo del vehículo.
8. `Mileage` - kilometraje (medido en km de acuerdo con las especificidades regionales del conjunto de datos).
9. `RegirtrationMonth` - mes de matriculación del vehículo.
10. `FuelType` - tipo de combustible.
11. `Brand` - marca del vehículo.
12. `NotRepaired` - vehículo con o sin reparación.
13. `DateCreated` - fecha de creación de perfil.
14. `NumberOfPictures` - cantidad de fotos del vehículo.
15. `PostalCode` - código postal del propietario del perfil (usuario).
16. `LastSeen` - fecha de la última vez que el usuario estuvo activo.

# Objetivo:

Construir y entrenar un modelo para determinar el valor de mercado de un automóvil considerando el tiempo de entrenamiento y predicción del modelo.

# Librerías usadas:

pandas | numpy | sklearn | catboost | lightgbm | time