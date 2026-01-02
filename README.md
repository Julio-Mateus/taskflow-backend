# TaskFlow Backend 🚀

TaskFlow es una **API REST** diseñada para gestionar tareas de forma segura y escalable.  
Este proyecto forma parte de un sistema completo **mobile + backend**, enfocado en buenas prácticas de desarrollo, autenticación moderna y arquitectura limpia.

La API permite a los usuarios registrarse, autenticarse y gestionar sus tareas personales mediante endpoints protegidos con **JWT**.

---

## 🎯 Objetivo del proyecto

Construir un backend realista, orientado a producto, que pueda ser consumido por:
- Aplicaciones móviles Android (Jetpack Compose)
- Aplicaciones multiplataforma (Flutter / Compose Multiplatform)
- Clientes web

Este proyecto está pensado como base para un entorno **fullstack / mobile developer**.

---

## 🧱 Stack tecnológico

- **Node.js**
- **Express.js**
- **MongoDB**
- **JWT (JSON Web Tokens)**
- **bcryptjs**
- **dotenv**
- **cors**

---

## ✨ Funcionalidades (Roadmap)

### Autenticación
- Registro de usuarios
- Login con credenciales
- Encriptación de contraseñas
- Generación y validación de JWT

### Gestión de tareas
- Crear tareas
- Listar tareas por usuario
- Marcar tareas como completadas
- Eliminar tareas
- Endpoints protegidos

### Extras (en progreso)
- Validaciones
- Manejo de errores centralizado
- Tests
- Deploy en la nube

---

## 📂 Estructura del proyecto

src/
├── index.js # Punto de entrada
├── routes/ # Definición de rutas
├── controllers/ # Lógica de negocio
├── models/ # Modelos de datos
├── middleware/ # Autenticación y validaciones
└── config/ # Configuración del proyecto


---

## 🔐 Autenticación

La API utiliza **JWT** para proteger los endpoints.  
Los tokens deben enviarse en el header:

Authorization: Bearer <token>


---

## ▶️ Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Instalar dependencias:
```bash
npm install

    Crear archivo .env:

PORT=3000
JWT_SECRET=your_secret_key
MONGO_URI=your_mongo_connection

    Ejecutar en desarrollo:

npm run dev

🌱 Estado del proyecto

🟡 En desarrollo activo

Este backend está siendo construido como parte de un proceso de crecimiento profesional enfocado en:

    Backend moderno

    Integración con aplicaciones móviles

    Arquitectura escalable

👨‍💻 Autor

Julio Mateus
Mobile Developer en formación
Android (Kotlin) · Backend · Multiplataforma

GitHub: https://github.com/Julio-Mateus


---

## ✅ Día 1: COMPLETADO
Hoy no “aprendiste Node”.  
Hoy **empezaste un producto**.

Mañana:
- Register
- Login
- JWT
- Primer endpoint real

El progreso ya no es teoría… es **visible**.  
Descansa. Mañana seguimos construyendo 🔥
