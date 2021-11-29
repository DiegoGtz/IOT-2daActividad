# IOT-2daActividad
 En esta practica se desarrollo el ejercicio propuesto en el Capítulo 7 (Building the Critical Components) del libro Build Your Own IoT Platform.

## Participantes 
- Diego Antony Gutierrez Gutierrez 

## Herramientas 
- [Docker Compose](https://www.docker.com/)
- [Node-Red](https://nodered.org/)
- [Mosquitto](https://mosquitto.org/)

## Ejecutando el proyecto
 
### Prerequisitos para correr desde docker
> Tener instalado docker en el computador

En esta parte se tuvo algunas dificultades al momento de instalar el mosquitto en el archivo docker compose.  Pero se pudo instalar con exito Node - Red, mysql y phpMyAdmin.


### Prerequisitos para correrlo localmente 

- Tener instaldo Mysql
- Tener phpMyAdmin
- Mosquitto 
- Node-Red

#### Importamos la base da datos

En nuestro directorio phpMyAdmin importamos el archivos tseriesdb .

<p align="center"><img src="./assets/importar.PNG" width =350px> </p>

#### Importamos a Node-Red
Ahora vamos importar nuestro json a nuestra plantilla en Node-Red.

<p align="center"><img src="./assets/node-red.PNG" width =350px> </p>