# 📱 NutriFOX - Control de Becas Alimenticias

Sistema completo compuesto por una app móvil (frontend) desarrollada en **React Native con Expo**, y un **backend en FastAPI**, diseñado para digitalizar el control de becas alimenticias en instituciones educativas.

---


---

## 🚀 Funcionalidades

### 📲 App móvil (React Native - Expo)

- Login con Firebase Auth
- Registro de alumnos desde la app
- Consulta de becas cobradas por número de control
- Registro de cobros por parte del personal de cafetería
- Visualización de historial personal por el alumno
- Panel de administrador con:
  - Lista de alumnos becados y no becados
  - Cambios de estado de beca
  - Gráfica de becas cobradas en tiempo real
  - Descarga de reporte semanal en PDF
- Gráficas de asistencia semanales por alumno
- Estilo visual moderno con degradados y diseño responsivo

---

### 🌐 Backend (FastAPI)

- API REST para registro y consulta de cobros
- Conexión a Firebase Auth para verificación de tokens
- Conexión a Firestore para persistencia de datos
- Generación automática de PDF con resumen semanal
- Soporte para filtros y ordenamiento de datos
- Seguridad basada en roles (`alumno`, `cafeteria`, `admin`)
- Desplegado en Render.com

---

## 🛠️ Cómo correr el proyecto

### 🔧 Requisitos previos

- Node.js y npm
- Python 3.10+
- Expo CLI (`npm install -g expo-cli`)
- Firebase CLI (opcional)
- Git
- Cuenta de Firebase (con Firestore y Auth habilitado)

---

### 🧪 1. Instalar y correr el frontend

```bash
cd cobroNutrifoxmovil
npm install
expo start
 Autores
Proyecto desarrollado por estudiantes del ITESZ como parte de la asignatura de Desarrollo Móvil:

👨‍💻 @moonherrera19 (GitHub)

📝 Licencia
Este proyecto fue desarrollado con fines académicos.
© 2025 NutriFOX Team – Todos los derechos reservados.

