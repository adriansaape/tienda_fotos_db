# 📸 PHP + React INTEGRACIÓN – Tienda de Fotos

## 📘 Proyecto: Tienda de Fotos en Línea <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="24px">

📌 **Descripción**

El proyecto **Tienda de Fotos** es un sistema web que permite a los usuarios **registrarse, iniciar sesión, comprar productos fotográficos (con o sin registro)**, gestionar pedidos y recibir notificaciones.  

Está desarrollado con **PHP + MySQL** en el backend y **React** en el frontend, gestionado bajo la metodología ágil **Scrum**, usando **Trello** para organización y **GitHub** para control de versiones.  

---

### 🎯 Objetivo del Proyecto
Construir una plataforma funcional que permita:
- Registro y login de usuarios.
- Visualización de productos en una interfaz dinámica desarrollada en **React**.
- Creación de pedidos con dos modalidades:
  - **Con registro** (usuario logueado).
  - **Sin registro** (compra directa).
- Envío de notificaciones al usuario sobre el estado de la compra.
- Gestión organizada de sprints bajo Scrum.

---

### 👨‍💻 ¿QUÉ SE LOGRÓ?
✔ Conexión a base de datos y creación de todas las tablas necesarias (usuarios, productos, pedidos, notificaciones).  
✔ Desarrollo de endpoints en **PHP** para registro de usuarios, login, listado de productos, creación de pedidos y envío de notificaciones.  
✔ Corrección de errores de claves foráneas y estructura de BD.  
✔ Implementación de opción de compra **con y sin registro**.  
✔ Interfaz de usuario en **React**, con componentes para cada módulo (login, registro, productos, pedidos).  
✔ Sprint 1 completado en Trello: repositorio, conexión a BD, registro de usuarios, listado de productos.  

---

<p align="right"> <h3>🛠 TECNOLOGÍAS UTILIZADAS:</h3> </p>

- 🌱 Backend: **PHP**
- 📫 Frontend: **React (JSX, Hooks, Fetch API)**
- ⚡ Base de Datos: **MySQL**
- 🎚️ Control de Versiones: **Git & GitHub**
- 👌 Gestión del Proyecto: **Scrum con Trello**

---

<img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="30px">&nbsp;***ROLES DE EQUIPO***

✔ Product Owner (PO): Define objetivos y prioridades.😉 <br>
✔ Scrum Master (SM): Facilita el proceso y da seguimiento en Trello.<br>
✔ Frontend Developer: Implementa la interfaz en **React**.<br>
✔ Backend Developer: Lógica PHP y conexión MySQL.<br>
✔ QA/Tester: Pruebas de flujo de pedidos y validaciones.<br>
✔ Documentador: Redacción de HU, checklist y README.<br>

---

# 📂 Estructura del Proyecto
```bash
📦 tienda_fotos
 ┣ 📂 backend
 ┃ ┣ conexion.php
 ┃ ┣ usuario_registro.php
 ┃ ┣ usuario_login.php
 ┃ ┣ producto_listar.php
 ┃ ┣ pedido_crear.php
 ┃ ┣ notificacion_enviar.php
 ┃ ┗ tienda_fotos_db.sql
 ┣ 📂 frontend
 ┃ ┣ 📂 src
 ┃ ┃ ┣ 📂 components
 ┃ ┃ ┃ ┣ Login.jsx
 ┃ ┃ ┃ ┣ Registro.jsx
 ┃ ┃ ┃ ┣ Productos.jsx
 ┃ ┃ ┃ ┣ Pedidos.jsx
 ┃ ┃ ┃ ┗ Notificaciones.jsx
 ┃ ┃ ┣ App.jsx
 ┃ ┃ ┗ index.js
 ┃ ┗ package.json
 ┣ README.md
