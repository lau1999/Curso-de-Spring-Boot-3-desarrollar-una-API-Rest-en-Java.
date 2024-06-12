# Sistema de Gestión de Médicos

## Descripción
Este proyecto es un sistema de gestión de médicos desarrollado en Java utilizando el framework Spring Boot. 
Proporciona una API REST para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre entidades de médicos.

El sistema permite realizar las siguientes operaciones sobre entidades de médicos:

- Registrar un nuevo médico con su información básica, incluyendo nombre, correo electrónico, teléfono, documento de identidad, especialidad y dirección.
- Listar médicos activos, permitiendo paginación y filtrado por especialidad.
- Actualizar la información de un médico existente, incluyendo su nombre, correo electrónico, teléfono, documento de identidad y dirección.
- Desactivar un médico, lo que lo marca como inactivo en el sistema.

## Tecnologías Utilizadas

- Java 17 : Especificado en la sección de propiedades ( <java.version>17</java.version>).
- Spring Boot : Utilizando varias dependencias de Spring Boot, incluido el spring-boot-starter-parentcomo padre del proyecto.
- Spring Boot Starter Web : Para construir aplicaciones web y servicios REST ( spring-boot-starter-web).
- Spring Boot DevTools : Para facilitar el desarrollo con herramientas adicionales ( spring-boot-devtools).
- Lombok : Para reducir el código estándar en Java ( org.projectlombok:lombok).
- Spring Boot Starter Test : Para pruebas unitarias e integración ( spring-boot-starter-test).
- Spring Data JPA : Para interactuar con bases de datos relacionales usando JPA ( spring-boot-starter-data-jpa).
- Ruta migratoria : Para la migración y gestión de la base de datos ( flyway-corey flyway-mysql).
- Conector MySQL : Para la conectividad con la base de datos MySQL ( mysql-connector-j).
- Validación de Spring Boot Starter : Para validación de datos ( spring-boot-starter-validation).

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

- `src/main/java/med/voll/api`: Contiene el código fuente del proyecto.
  - `controller`: Contiene los controladores REST.
  - `direccion`: Contiene las clases relacionadas con la dirección.
  - `medico`: Contiene las clases relacionadas con los médicos.
- `src/test/java`: Contiene las pruebas unitarias.

## Instrucciones de Uso

1. Clona el repositorio o descarga el código fuente.
2. Importa el proyecto en tu IDE preferido.
3. Asegúrate de tener configurado Java y Maven en tu entorno.
4. Ejecuta la aplicación.
5. Accede a la API REST utilizando herramientas como Insomnia.
6.  CRala la base de datos en Myqsl workben
