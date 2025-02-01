# API RESTful con Spring y Angular

Este proyecto es una aplicación web que utiliza una API RESTful desarrollada con Spring Boot en el backend y una interfaz de usuario construida con Angular en el frontend.

## Características

- **Backend**: Implementado con Spring Boot, proporciona una API RESTful para gestionar [especificar recursos, por ejemplo, "usuarios", "productos"].
- **Frontend**: Desarrollado con Angular, ofrece una interfaz de usuario interactiva para interactuar con la API.
- **Base de datos**: MySQL para la creación de tablas y creación de registros.

## Requisitos previos

- **Java 17**: Asegúrate de tener instalada la versión 17 de Java.
- **Node.js y npm**: Necesarios para ejecutar la aplicación Angular.
- **Angular CLI**: Instalado globalmente para facilitar el desarrollo de Angular.
- **Maven**: Para gestionar las dependencias y construir el proyecto Spring Boot.
- **MySQL**: Para construir base de datos y recibir los datos.

## Instalación

1. **Clonar el repositorio**:

   ```bash
   git clone https://github.com/Calvinnn23/API-REST-Spring-Angular.git
   cd API-REST-Spring-Angular
   ```

2. **Configuración del Backend**:

   - Navega al directorio del backend:

     ```bash
     cd backend
     ```

   - Configura la conexión a la base de datos en el archivo `application.properties` o `application.yml` según corresponda.

   - Construye y ejecuta la aplicación Spring Boot:

     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

   La API estará disponible en `http://localhost:8080`.

3. **Configuración del Frontend**:

   - Navega al directorio del frontend:

     ```bash
     cd ../frontend
     ```

   - Instala las dependencias de Angular:

     ```bash
     npm install
     ```

   - Ejecuta la aplicación Angular:

     ```bash
     ng serve
     ```

   La aplicación estará disponible en `http://localhost:4200`.

## Uso

Proporciona instrucciones sobre cómo utilizar la aplicación, por ejemplo, cómo realizar operaciones CRUD, autenticación, etc.

