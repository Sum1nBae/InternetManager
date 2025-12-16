# InternetManager

InternetManager es un sistema web orientado a la gestión de un cibercafé,
permitiendo el control de sesiones de uso, administración de máquinas
y registro de actividad de los usuarios de manera estructurada y eficiente.

---

## 1. Descripción del proyecto

El presente proyecto tiene como finalidad desarrollar un sistema de gestión
para cibercafés que facilite el control del tiempo de uso de las máquinas,
la administración de sesiones activas y el manejo centralizado de la
información, utilizando una arquitectura cliente-servidor.

El sistema se divide en frontend y backend, permitiendo un desarrollo modular,
escalable y colaborativo.

---

## 2. Objetivo general

Desarrollar una aplicación web que permita administrar de forma eficiente
las sesiones de un cibercafé, mejorando la organización, el control del
tiempo de uso y la disponibilidad de las máquinas.

---

## 3. Tecnologías utilizadas

- **HTML5**: Estructura del sistema.
- **JavaScript**: Lógica del frontend y comunicación con el backend.
- **PHP**: Procesamiento de solicitudes en el servidor.
- **MariaDB / MySQL**: Gestión de la base de datos.
- **Tailwind CSS**: Diseño y estilos de la interfaz gráfica.

---

## 4. Arquitectura del sistema

El sistema sigue una arquitectura cliente-servidor:

- **Frontend**: Encargado de la interfaz de usuario, la lógica de presentación
  y el consumo de servicios mediante JavaScript.
- **Backend**: Responsable de la lógica del negocio, acceso a la base de datos
  y manejo de las sesiones.
- **Base de datos**: Almacena la información relacionada con sesiones,
  máquinas y registros del sistema.

---

## 5. Estructura del proyecto

InternetManager/
│
├── backend/
│   ├── conexion.php
│   ├── iniciar_sesion.php
│   ├── finalizar_sesion.php
│   ├── editar_sesion.php
│   ├── eliminar_sesion.php
│   ├── obtener_maquinas.php
│   ├── obtener_sesiones.php
│   └── obtener_sesiones_activas.php
│
├── js/
│   ├── api.js
│   ├── main.js
│   ├── index.js
│   │
│   ├── services/
│   │   ├── dashboard.service.js
│   │   └── sesiones.service.js
│   │
│   ├── state/
│   │   └── estado.js
│   │
│   └── ui/
│       ├── ui.dashboard.js
│       ├── ui.maquinas.js
│       ├── ui.messages.js
│       └── ui.sesiones.js
│
├── index.html
└── README.md

---

## 6. Flujo de trabajo con Git

El desarrollo del proyecto se realizó utilizando control de versiones con Git
y la plataforma GitHub, aplicando un flujo de trabajo basado en ramas:

- **main**: Rama estable del proyecto.
- **branch-axel**: Desarrollo del frontend.
- **branch-benito**: Desarrollo del backend.

La integración de cambios se realiza mediante Pull Requests para garantizar
un historial claro y organizado.

---

## 7. Colaboradores

- **Axel Morales** – Desarrollo Frontend
- **Benito Cortés** – Desarrollo Backend

---

## 8. Estado del proyecto

El proyecto se encuentra en desarrollo y continúa en proceso de integración
de funcionalidades y mejoras.
