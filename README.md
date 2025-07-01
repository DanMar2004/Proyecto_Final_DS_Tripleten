# Proyecto_Final_DS_Tripleten
## Modelo machine learning para clasificacion de clientes para detectar el abandono del servicio de la Empresa de telecomunicaciones Interconnect

En este caso practico usaremos 4 datasets que contiene informacion de los clientes activos y de los clientes que dejaron el servicio, con esta informacion se entrenaran diferentes modelos para poder predecir si un cliente quiere abandonar el servicio.

### Objetivo
Crear un modelo ML clasificatorio obteniendo un score en AUC-ROC mayor a .85

### Resultados 
* De todos los modelos entrenados el mejor score lo obtuvo la red neuronal densa secuencial aunque varios modelos como bosque aleatorio, XGBoost y otros estuvieron cerca de igualar el score
* Se identifico cuales son las caracteristicas que mas relacion tienen con el abandono como el tipo de contrato mes a mes o el pago en cheque, con esta informacion se deberia generar mejoras en la experiencia del usuario
  
