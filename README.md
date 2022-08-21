# Reto1-IOT
## Pareja 2

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Objetivos

- Extender el código fuente del laboratorio 1, para tomar lectura de la luminosidad.
- Implementar el correspondiente sensor para tomar lectura de la luz

Integrantes

- Andres Benitez
- William Fernando Sánchez Pulido

## Estructura de Carpetas

- luminosidad_wfs_ab/
- luminosidad_wfs_ab.ino
  
## Despliegue

Ejecutar el archivo en el correspondiente arduino IDE
Sleccionar la placa base ESP8266.
Incluir las librerias:

```sh
#include <ESP8266WiFi.h>
#include <WiFiClientSecure.h>
#include <time.h>
#include <PubSubClient.h>
#include "DHT.h"
```

