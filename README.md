# Microservicio 2 - Eureka

## Tecnologías Utilizadas:

SpringBoot (Versión 3.2.0)<br>
Java (Versión 17.+.+) Compatible con la version de SpringBoot<br>

## Instrucciones de Ejecución:

jecuta el proyecto en el IDE de java (de tu preferencia), eso hara que se reconozca el proyecto y maven instale las dependencias. <br>

### Realiza la ejecucion de los Microservicios en el siguiente orden:

- Config
- Eureka (actual)
- Client
- Vehicle
- Gateway

## API Endpoint:

Endpoint de Cliente: http://localhost:8090/api/client/<br>
Endpoint de Vehicle: http://localhost:9090/api/vehicle/<br>
<br>
Endpoint de Eureka: http://localhost:8761/eureka<br>
<br>
Endpoint del gateway: http://localhost:8080/<br>
<br>

## Enlaces de los otros microservicios:

config-url: https://github.com/Maur025/Microservice_CS_Config.git<br>
client-url: https://github.com/Maur025/Microservice_CS_Client.git<br>
vehicle-url: https://github.com/Maur025/Miroservice_CS_vehicle.git<br>
gateway-url: https://github.com/Maur025/Microservice_CS_gateway.git<br>
