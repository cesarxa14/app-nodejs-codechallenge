# Solución - César Torres Lara :smiley:

# Diagrama de Aplicaciones

![Diagrama de Aplicaciones](https://github.com/cesarxa14/app-nodejs-codechallenge/blob/feature/cesar/Diagrama%20de%20aplicaciones.png)

# Herramientas

He usado las siguientes herramientas para el desarrollo de mi reto técnico.

<ol>
  <ul><strong>VS Code</strong>: Editor de código fuente</ul>
  <ul><strong>NodeJS</strong>: Entorno de ejecución Javascript en el servidor</ul>
  <ul><strong>Typescript</strong>: Lenguaje de programación como extensión de Javascript, para el tipado de datos</ul>
  <ul><strong>MongoDB</strong>: Sistema de datos NoSQL para el almacenamientos de datos</ul>
  <ul><strong>Docker</strong>: Virtualiza las aplicaciones en contenedores para ejecutar en diferentes entornos</ul>
  <ul><strong>Docker-compose</strong>: Permite gestionar multicontenedores de Docker mediante un archivo YAML</ul>
  <ul><strong>Kafka</strong>: Proporciona una arquitectura de transmisión de datos entre microservicios</ul>
  <ul><strong>Swagger</strong>: Permite diseñar, construir y documentar APIs de manera sencilla.</ul>   
</ol>


# Requerimientos Previos:

Para poder ejecutar y ver los logs del proyecto, recomiendo descargar **Docker Desktop** para tener una interfaz gráfica mas intuitiva de como se estan manejando los contenedores y ver los logs del sistema.

Link de la página oficial de Docker Desktop para poder descargarlo: https://www.docker.com/products/docker-desktop/

No olvides tener los puertos **3001** y **3002** libres para poder ejecutar los microservicios.

# Instalación y Ejecución

Para poder ejecutar la aplicación debe ubicar en la ruta raiz del proyecto y ejecutar en la consola el siguiente comando: `docker-compose up -d`. De esta forma se empezaran a iniciar en segundo plano los contenedores definidos en el archivo **docker-compose.yml**.

![Docker containers](https://github.com/cesarxa14/app-nodejs-codechallenge/blob/feature/cesar/Docker%20screenshot.png)

![Microservicio Transaction](https://github.com/cesarxa14/app-nodejs-codechallenge/blob/feature/cesar/Microservice%20transaction%20docker%20log.png)

![Microservicio Antifraud](https://github.com/cesarxa14/app-nodejs-codechallenge/blob/feature/cesar/Microservice%20antifraud%20docker%20log.png)



**NOTA:** Para poder entrar como cliente, se hace uso de Swagger donde esta documentado el API REST y así poder crear transacciones de manera manual.

Swagger se encuentra ubicado en `http://localhost:3001/documentation/`.

![Swagger](https://github.com/cesarxa14/app-nodejs-codechallenge/blob/feature/cesar/Swagger%20screenshot.png)

# Observaciones

- Elegí usar Mongoose en lugar de TypeORM principalmente debido a mi familiaridad y experiencia previa con el ecosistema de MongoDB y Node.js. Mongoose me proporciona una interfaz intuitiva y orientada a objetos para interactuar con MongoDB, lo que me resulta cómodo y eficiente. Aunque tambien tengo conocimientos de TypeORM y conozco sus ventajas, como su soporte para múltiples bases de datos relacionales, decidí utilizar Mongoose en mi proyecto.






