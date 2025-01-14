# 📚 ForoHub API

La siguiente aplicación es la creación de un API REST de un Foro donde las personas pueden realizar aportes y comentarios sobre diversos temas. Este foro está desarrollado para una comunidad educativa, permitiendo a los estudiantes compartir y resolver sus dudas.

## 🌟 Funcionalidades de la API

Nuestra API se centra específicamente en los tópicos y permite a los usuarios:

- 🗒️ **Crear un nuevo tópico**.
- 💬 **Mostrar todos los tópicos creados**.
- ✅ **Mostrar un tópico específico**.
- ✏️ **Actualizar un tópico**.
- ⛔ **Eliminar un tópico**.

  ![Intellij - ForoHub](https://github.com/user-attachments/assets/3fd2f31d-c080-4de3-b455-4fd0f7800703)


## 🎯 Objetivos del Proyecto

### 🎯 Objetivo General

**Crear una API REST con los métodos CRUD (Create, Read, Update, Delete) para el registro, ingreso, eliminación y visualización de tópicos y usuarios a través de una interfaz creada mediante Spring Boot, con el fin de brindar un espacio seguro y estructurado para compartir conocimientos, resolver dudas y construir una comunidad educativa.**

### 📌 Objetivos Específicos

- Configurar el entorno en Java.
- Construir la base de datos.
- Crear el endpoint para registrar un nuevo tópico.
- Crear el endpoint para listar los tópicos.
- Crear un endpoint para actualizar un tópico.
- Crear un endpoint para eliminar un tópico.
- Autenticar a los usuarios de la API mediante Spring Security y generar el token con JWT.

## 🛠️ Tecnologías Utilizadas

- **Backend**: Spring Boot, Java, JPA.
- **Base de Datos**: MySQL.
- **Herramientas de Desarrollo**: Insomnia (para pruebas API).

## ✨ Funcionalidades Principales

- **Registro y autenticación de usuarios**.
- **Creación y gestión de foros**: Organización de tópicos y comentarios.

## 🔧 Instalación y Configuración

### ⚙️ Requisitos Previos

- Java [versión 17]
- Base de datos MySQL [versión 8.1]
- Gestor de paquetes (Maven)
- Spring Boot 3

### 📦 Dependencias Necesarias

- MySQL DRIVER
- Spring JPA
- Spring Validation
- Spring Web
- Flyway
- Flyway-mysql
- Spring Devtools
- Lombok
- Spring Security
- Java-jwt

**Enlace del repositorio**: [java-jwt](https://github.com/auth0/java-jwt)

### 📋 Configuración del Proyecto

Para comenzar, se utilizó el Spring Initializr: [Spring Initializr](https://start.spring.io/), y se agregaron las dependencias mencionadas.

### 🗄️ Configuración de la Base de Datos

1. Crea una base de datos llamada `foro` en la base de datos de tu preferencia (ten en cuenta que en el proyecto se utilizó MySQL; si deseas usar otra base de datos, debes modificar las dependencias en el `pom.xml`).
2. Ejecuta los scripts de migración en el directorio `db/migrations` utilizando Flyway:
   ```bash
   flyway migrate
## 🚀 Uso de la Aplicación

### 🔐 Registro de Usuario con Login y Contraseña

- **Método**: POST
- **URL**: `/usuarios`
- **Insomnia**: Registrar usuarios

 ![Insomnia - registrar usuarios](https://github.com/user-attachments/assets/5202f9c8-f15b-4b9e-bf70-02b239d648ba) 

### 📝 Registro de un Nuevo Tópico

- **Método**: POST
- **URL**: `/topicos`
- **Insomnia**: Registrar tópicos

 ![Insomnia - registrar topicos](https://github.com/user-attachments/assets/ebb1475c-38d3-417a-bb94-ac305d5c61a3) 

### 📄 Listado de Tópicos Existentes

- **Método**: GET
- **URL**: `/topicos`
- **Insomnia**: Listar tópicos

 ![Insomnia - listar topicos](https://github.com/user-attachments/assets/ead288fd-e9c1-4268-b1e5-a96ab8593f54) 

### 🔍 Detalle de un Tópico

- **Método**: GET
- **URL**: `/topicos/{id}`
- **Insomnia**: Detallando tópicos

 ![Insomnia - detallando topicos](https://github.com/user-attachments/assets/498a192d-9206-4e28-975c-858ba2c62859) 

### ✏️ Actualizar un Tópico

- **Método**: PUT
- **URL**: `/topicos/{id}`
- **Insomnia**: Actualizar tópicos

 ![image](https://github.com/user-attachments/assets/ef518320-2310-4112-8185-77a67ca23e72) 

### 🗑️ Eliminar un Tópico Existente

- **Método**: DELETE
- **URL**: `/topicos/{id}`
- **Insomnia**: Eliminar tópicos

  ![Insomnia - delete topico exitosamente](https://github.com/user-attachments/assets/62d12a8f-d60e-4097-b14a-1e5d09a1e666)







