# Challenge ONE | Back End | Foro Alura 

<p align="center" >
     <img width="200" heigth="200" src="https://user-images.githubusercontent.com/91544872/209678377-70b50b21-33de-424c-bed8-6a71ef3406ff.png">
</p>


## Table of Contents

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Funcionalidades](#funcionalidades)

---

## Descripción del Proyecto

¡Desafío del Challenge Back End!

El foro alura es un lugar donde todos los alumnos de la plataforma alura pueden colocar sus preguntas sobre determinados cursos,
este mágico lugar está lleno de mucho aprendizaje y de colaboración entre alumnos, profesores y moderadores.

Ya sabemos para que sirve el foro y sabemos cómo se ve, pero ¿sabemos cómo funciona por detrás? Es decir ¿dónde se almacenan las informaciones? ¿cómo se tratan esos datos para que se relacione un tópico con una respuesta, o como se relacionan los usuarios con las respuestas de un tópico?

La funcionalidad de la API se centra en un CRUD que permite:

- Crear un nuevo registro.
- Mostrar todos los registros.
- Mostrar un registro específico.
- Actualizar un registro.
- Eliminar un registro.

Además, se incluirán búsquedas personalizadas, tales como:

- Búsqueda de un tópico por ID de un curso.
- Búsqueda de un tópico o respuesta por ID de un autor.
- Búsqueda de una respuesta por ID de un tópico.

---

## Funcionalidades

El Foro Alura consta de cuatro entidades: Usuario, Curso, Tópico y Respuesta. Se pueden realizar acciones CRUD en estas entidades, así como búsquedas personalizadas. Se han creado endpoints específicos para registrar la información necesaria y ejecutar las acciones correspondientes. Para una mejor comprensión, se utiliza Swagger para documentar la API.

### Puesta en Marcha

1. Iniciar el servidor de Spring Boot.
2. Acceder a [http://localhost:8080/doc/swagger-ui/index.html](http://localhost:8080/doc/swagger-ui/index.html).
3. Abrir autenticacion-controller y generar el token para autenticarse, ingresando usuario y contraseña de la siguiente manera:
   
   ```json
   {
      "nombre": "admin",
      "contrasena": "admin"
   }

## Código fuente

ForoAlura está desarrollado en Java implementando Spring Boot.

* [Repositorio](https://github.com/juanbasanes/ForoAlura)

* Desarrollado por Juan Basanes Cantoni