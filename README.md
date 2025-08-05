# Academic System Backend / Backend del Sistema Académico

## Descripción / Description

**ES:**  
Aplicación backend desarrollada con Spring Boot para gestionar estudiantes, profesores, asignaturas y calificaciones. Integra MySQL para almacenamiento de datos, Spring Data JPA para operaciones con la base de datos, y Lombok para reducir código repetitivo. Soporta relaciones muchos-a-muchos (profesores ↔ asignaturas) y está diseñada para ser escalable y mantenible.

**EN:**  
Spring Boot backend application to manage students, teachers, subjects, and grades. Uses MySQL for data storage, Spring Data JPA for database operations, and Lombok to reduce boilerplate code. Supports many-to-many relationships (teachers ↔ subjects) and is built for scalability and maintainability.

---

## Funcionalidades clave / Key Features

- Gestión de entidades: estudiantes, profesores, asignaturas y calificaciones  
- Relaciones muchos-a-muchos entre profesores y asignaturas  
- Persistencia robusta con Spring Data JPA y MySQL  
- Código limpio y mantenible con Lombok  
- Estructura preparada para añadir tests y mejorar funcionalidad  

---

## Tecnologías / Technologies

- Java 17+  
- Spring Boot  
- Spring Data JPA  
- MySQL  
- Lombok  

---

## Instalación y ejecución / Installation and Running

**ES:**  
1. Clona el repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/academic-system.git

2. Configura tu base de datos MySQL y actualiza application.properties con tus credenciales.

3. Ejecuta la aplicación con Maven o tu IDE preferido:
    ```bash
    ./mvnw spring-boot:run

**EN:**  
1. Clone the repository:
    ```bash
    git clone https://github.com/tu-usuario/academic-system.git

2. Configure your MySQL database and update application.properties with your credentials.

3. Run the application using Maven or your preferred IDE:
    ```bash
    ./mvnw spring-boot:run

## Testing
**ES:**
Actualmente no incluye tests, pero la estructura está preparada para añadirlos en futuras versiones.

**EN:**
Currently does not include tests, but the structure is prepared to add them in future versions.
