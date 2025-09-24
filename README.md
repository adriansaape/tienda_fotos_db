# 📸 PHP INTEGRACIÓN – Tienda de Fotos

## 📘 Proyecto: Tienda de Fotos en Línea <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="24px">

📌 **Descripción**

El proyecto **Tienda de Fotos** es un sistema web que permite a los usuarios **registrarse, iniciar sesión, comprar productos fotográficos (con o sin registro)**, gestionar pedidos y recibir notificaciones.  

Está desarrollado en **PHP** con conexión a **MySQL**, implementando estilos en **HTML + CSS** y gestionado bajo la metodología ágil **Scrum** usando **Trello** para organización y **GitHub** para control de versiones.  

---

### 🎯 Objetivo del Proyecto
Construir una plataforma funcional que permita:
- Registro y login de usuarios.
- Visualización de productos en una interfaz amigable (no en formato JSON).
- Creación de pedidos con dos modalidades:
  - **Con registro** (usuario logueado).
  - **Sin registro** (compra directa).
- Envío de notificaciones al usuario sobre el estado de la compra.
- Gestión organizada de sprints bajo Scrum.

---

### 👨‍💻 ¿QUÉ SE LOGRÓ?
✔ Conexión a base de datos y creación de todas las tablas necesarias (usuarios, productos, pedidos, notificaciones, formularios).  
✔ Desarrollo de **plugins en PHP** para: registrar usuarios, login, listar productos, crear pedidos y enviar notificaciones.  
✔ Corrección de errores de claves foráneas y estructura de BD.  
✔ Implementación de opción de compra **con y sin registro**.  
✔ Interfaz más organizada con HTML y menús de navegación.  
✔ Sprint 1 completado en Trello: repositorio, conexión a BD, registro de usuarios, listar productos.  

---

<p align="right"> <h3>🛠 TECNOLOGÍAS UTILIZADAS:</h3> </p>

- 🌱 Lenguaje Backend: **PHP**
- 📫 Lenguaje Frontend: **HTML5, CSS3**
- ⚡ Base de Datos: **MySQL**
- 🎚️ Control de Versiones: **Git & GitHub**
- 👌 Gestión del Proyecto: **Scrum con Trello**

---

<img src="https://media.giphy.com/media/ObNTw8Uzwy6KQ/giphy.gif" width="30px">&nbsp;***ROLES DE EQUIPO***

✔ Product Owner (PO): Define objetivos y prioridades.😉 <br>
✔ Scrum Master (SM): Facilita el proceso y da seguimiento en Trello.<br>
✔ Frontend Developer: Diseña la interfaz y formularios.<br>
✔ Backend Developer: Lógica PHP y conexión MySQL.<br>
✔ QA/Tester: Prueba de plugins y flujo de pedidos.<br>
✔ Documentador: Redacción de HU, checklist y README.<br>

---

# 📂 Estructura del Proyecto
```bash
📦 tienda_fotos
 ┣ 📂 plugins
 ┃ ┣ usuario_registro.php
 ┃ ┣ usuario_login.php
 ┃ ┣ producto_registrar.php
 ┃ ┣ producto_listar.php
 ┃ ┣ pedido_crear.php
 ┃ ┣ notificacion_enviar.php
