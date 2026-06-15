# TuBiblioWeb

Plataforma web desarrollada como Proyecto para la gestión de una biblioteca física, permitiendo a los usuarios consultar el catálogo, reservar libros y gestionar su cuenta de forma online.

## Características principales

### Usuarios

- Registro de usuarios
- Inicio y cierre de sesión
- Verificación de cuenta mediante correo electrónico
- Gestión de sesiones
- Consulta de reservas activas

### Catálogo de libros

- Búsqueda de libros
- Filtros por categorías
- Visualización de detalles
- Sistema de valoración mediante "Me gusta"
- Recomendaciones de contenido

### Sistema de reservas

- Calendario interactivo
- Selección de fecha y hora
- Control de disponibilidad
- Confirmación automática de reservas
- Envío de notificaciones por correo electrónico

### Administración

- Gestión de libros
- Gestión de autores
- Gestión de usuarios
- Altas, bajas y modificaciones (CRUD)
- Exportación de usuarios a Excel
- Generación de códigos QR para usuarios
- Generación automática de documentos PDF

---

## Tecnologías utilizadas

### Backend

- PHP
- MySQL / MariaDB

### Frontend

- HTML5
- CSS3
- JavaScript
- jQuery

### Librerías

- SweetAlert2
- FullCalendar
- Swiper.js
- Select2
- PHPMailer
- FPDF
- PHPQRCode

### Infraestructura

- Apache2
- Linux
- VirtualBox

---

## Base de datos

La aplicación utiliza MySQL/MariaDB para almacenar:

- Usuarios
- Libros
- Autores
- Reservas
- Valoraciones
- Configuración del sistema

---

## Seguridad implementada

- Validación de formularios
- Protección básica frente a inyección SQL
- Escapado de caracteres especiales
- Protección básica frente a ataques XSS
- Gestión de sesiones de usuario

---

## ⚙ Instalación

### Requisitos

- Apache2
- PHP 8+
- MariaDB / MySQL
- phpMyAdmin (opcional)

### Pasos

1. Clonar el repositorio

```bash
git clone https://github.com/CristianLRr/TuBiblioWeb.git
