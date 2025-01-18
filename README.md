# LiterAlura 📚
LiterAlura es una aplicación de consola desarrollada en Java utilizando Spring Boot, Spring Data JPA, y PostgreSQL. Esta herramienta interactúa con la API de Gutendex para buscar libros, almacenarlos en una base de datos local, y brindar múltiples funcionalidades relacionadas con la gestión de libros y autores.


## 📖 Descripción del Proyecto

LiterAlura nace con el propósito de combinar el aprendizaje en desarrollo backend con la exploración literaria, permitiendo a los usuarios:

- Buscar libros por su título en la API de Gutendex.
- Registrar libros en una base de datos local.
- Consultar libros y autores con diversas opciones de filtrado.

## 🚀 Funcionalidades

1. Buscar Libro por Título y Guardarlo en la Base de Datos
- Utiliza la API de Gutendex para buscar un libro por su título.
- Guarda el libro en la base de datos si no está registrado previamente.

2. Listar Libros Registrados
- Muestra una lista de todos los libros registrados en la base de datos.

3. Listar Autores Registrados
- Presenta una lista de todos los autores registrados en la base de datos.

4. Listar Autores Vivos en un Determinado Año
- Permite ingresar un año para listar los autores que estaban vivos en ese período.

5. Listar Libros por Idioma
- Filtra libros registrados según su idioma (por ejemplo: ES, EN, FR, PT)
## 🛠️ Tecnologías Utilizadas
- Lenguaje: Java 17
- Frameworks: Spring Boot, Spring Data JPA
- Base de Datos: PostgreSQL
- API Externa: Gutendex API
- IDE: IntelliJ IDEA
## ⚙️ Requisitos del Proyecto

1. Java 17
2. Maven
3. PostgreSQL instalado y configurado:
- Crear una base de datos llamada literalura.
- Configurar las credenciales en application.properties
## 🚀 Cómo Ejecutar el Proyecto

1. Clona este repositorio:

```bash
  git clone https://github.com/tu-usuario/literalura.git

```
2. Configura las credenciales de tu base de datos en application.properties:

```bash
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
```
3. Compila y ejecuta el proyecto:

```bash
mvn clean install
mvn spring-boot:run
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=tu_usuario
spring.datasource.password=tu_contraseña
```
4. Accede a los endpoints desde Postman o la consola.
## 💬 Feedback
Tu retroalimentación es muy valiosa para mejorar este proyecto. Si tienes alguna sugerencia, problema o idea para agregar funcionalidades, no dudes en contactarme en mi e-mail: gabrielabo.dev@protonmail.com o abrir un issue en este repositorio.
## 📧 Contacto
Puedes encontrarme en:

- GitHub: https://github.com/GabbyGeek
- LinkedIn: Tu Perfil: https://www.linkedin.com/in/lgabrielabonilla/
## 🌟 Contribuciones
Las contribuciones son bienvenidas. Si deseas colaborar, sigue estos pasos:

Haz un fork del repositorio.
Crea una nueva rama para tu funcionalidad: git checkout -b feature/nueva-funcionalidad.
Realiza tus cambios y haz un commit: git commit -m 'Agregué una nueva funcionalidad'.
Envía un pull request
## 📢 Agradecimientos
- Al equipo de Alura LATAM y ORACLE por su programa educativo.
- A la comunidad de desarrolladores que comparte sus conocimientos y apoya a otros.
