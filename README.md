**FORO HUB API**

La siguiente aplicación es la creación de un API REST de un Foro entre donde las personas pueden realizar aportes, comentarios de diversos temas. 
Este foro esta desarrollado en base a una comunidad educativa para que los estudiantes puedan compartir y resolver sus dudas.


**Funcionalidades de la API**
Nuestra API va a centrarse específicamente en los tópicos, y debe permitir a los usuarios:

🗒️ Crear un nuevo tópico.

💬 Mostrar todos los tópicos creados.

✅ Mostrar un tópico específico.

✏️ Actualizar un tópico.

⛔ Eliminar un tópico.

![Intellij - ForoHub](https://github.com/user-attachments/assets/d98b47cd-1430-400b-8e3e-59cd911147ba)


Al final de nuestro desarrollo tendremos una API REST con las siguientes funcionalidades

1.	API con rutas implementadas siguiendo las mejores prácticas del modelo REST;
2.	Validaciones realizadas según reglas de negocio;
3.	Implementación de una base de datos para la persistencia de la información;
4.	Servicio de autenticación/autorización para restringir el acceso a la información



**Objetivo General**
Crear una API REST con los métodos CRUD (Create, Read, Update, Delete) para el registro, ingreso, eliminación y visualización de tópicos y usuarios a través de una interfaz creada mediante SpringBoot 
con el fin de Brindar un espacio seguro y estructurado para compartir conocimientos, resolver dudas y construir una comunidad educativa

**Objetivos Especificos**

• Configurar el entorno en Java.

• Construir la base de datos.

• Crear el endpoint para registrar un nuevo topico.

• Crear el endpoint para listar los tópicos.

• Crear el endpoint para listar los tópicos.

• Crear un endpoint para actualizar un tópico.

• Crear un endpoint para eliminar un tópico.

• Autenticar los usuarios de la API mediante Spring Security y generación del token con JWT.


**Tecnologías Utilizadas**
- Backend: Spring Boot, Java, JPA.
- Base de Datos: MySQL.
- Herramientas de Desarrollo: Insomnia (para pruebas API).

**Funcionalidades Principales**
- Registro y autenticación de usuarios.
- Creación y gestión de foros

**Tecnologías Utilizadas**
- Backend: Spring Boot, Java, JPA.
- Base de datos: MySQL.
- Herramientas de desarrollo: Insomnia (para pruebas API).

**Funcionalidades Principales**
- Registro y autenticación de usuarios
- Creación y gestión de foros: Organización de tópicos y comentarios.

**Instalación y Configuración**

Configuración al crear el proyecto con Spring Initializr  https://start.spring.io/:

* Java (versión 17 en adelante)
* Maven (Initializr utiliza la versión 4)
* Spring Boot
* Proyecto en formato JAR


Dependencias para agregar al crear el proyecto con Spring Initializr:

* Lombok
* Spring Web
* Spring Boot DevTools
* Spring Data JPA
* Flyway Migration
* MySQL Driver
* Validation
* Spring Security
* Java-jwt Enlace del repositorio donde podemos revisar las instrucciones para agregar la dependencia: https://github.com/auth0/java-jwt
  


**Configuración de la base de datos**
1.- Crea una base de datos en la Base de datos de su preferencia (tenga en cuenta que en el proyecto se utilizó MySQL si quiero usar otra Base de datos debe modificar las dependencias en el pom.xml).
2.- Ejecuta los scripts de migración en el directorio db/migrations utilizando Flyway:  flyway migrate


**Uso de la aplicacion**

Registro de usuario con Login y Contraseña. Metodo POST

![Insomnia - registrar usuarios](https://github.com/user-attachments/assets/5202f9c8-f15b-4b9e-bf70-02b239d648ba)

Registro de un nuevo Topico. Metodo POST

![Insomnia - registrar topicos](https://github.com/user-attachments/assets/ebb1475c-38d3-417a-bb94-ac305d5c61a3)

Listado de topicos existentes. Metodo GET

![Insomnia - listar topicos](https://github.com/user-attachments/assets/ead288fd-e9c1-4268-b1e5-a96ab8593f54)

Detalle de un topico. Metodo GET

![Insomnia - detallando topicos](https://github.com/user-attachments/assets/498a192d-9206-4e28-975c-858ba2c62859)

Actualizar un topico. Metodo PUT

![image](https://github.com/user-attachments/assets/ef518320-2310-4112-8185-77a67ca23e72)


Eliminando un topico existente. Metodo DELETE

![Insomnia - delete topico exitosamente](https://github.com/user-attachments/assets/62d12a8f-d60e-4097-b14a-1e5d09a1e666)





