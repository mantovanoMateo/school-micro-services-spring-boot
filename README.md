# School Microservices - Spring Boot

Este repositorio contiene una aplicación desarrollada con Spring Boot que implementa una arquitectura de microservicios para la gestión de un sistema escolar.

## Arquitectura

La aplicación está compuesta por los siguientes microservicios:

- **Config Server**: Proporciona configuración centralizada para todos los microservicios.
- **Discovery Service**: Maneja el registro y descubrimiento de servicios utilizando Netflix Eureka.
- **API Gateway**: Actúa como un punto de entrada para los clientes, gestionando las peticiones hacia los microservicios.
- **School Service**: Gestiona la información relacionada con las escuelas.
- **Student Service**: Gestiona la información de los estudiantes.

## Prerrequisitos

- **Java 11** o superior
- **Maven 3.6.0** o superior
- **Docker** para ejecutar los microservicios en contenedores.

## Configuración

1. Clona este repositorio:
   ```bash
   git clone https://github.com/mantovanoMateo/school-micro-services-spring-boot.git
