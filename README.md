# Primerapartedelproyecto
# 🌱 Aplicación de Seguimiento de Huertas Urbanas

Este proyecto es una plataforma para el monitoreo y gestión de huertas urbanas, permitiendo a los usuarios registrar cultivos, llevar un seguimiento de las cosechas y compartir consejos prácticos con la comunidad.

## 🚀 Tecnologías Utilizadas

- **Backend:** NestJS con PostgreSQL (Prisma ORM) y MongoDB.
- **Frontend:** Next.js
- **Base de datos:** PostgreSQL para datos estructurados y MongoDB para almacenamiento de consejos/comentarios.
- **Documentación:** Swagger
- **CI/CD:** GitHub Actions

## 📁 Estructura del Proyecto

proyecto-api/ 
─ README.md 
─ github │ 
─ workflows/  backend/  src/ main.ts / app.module.ts / prisma/  mongo/ modules/ │ │ │ └── [feature]/ │ │ │ ├── dto/ │ │ │ ├── entities/ │ │ │ ├── controllers/ │ │ │ └── services/ │ │ └── config/ │ ├── prisma/ │ │ └── schema.prisma │ ├── test/ │ └── swagger/ ├── frontend/ │ ├── src/ │ │ ├── app/ │ │ ├── components/ │ │ ├── lib/ │ │ ├── api/ │ │ └── styles/ │ ├── public/ │ └── tests/ └── docs/ ├── api/ ├── database/ └── guides/


## 📌 Funcionalidades Principales

- Registro y seguimiento de cultivos.
- Registro de cosechas con fechas y notas.
- Visualización de estadísticas de producción.
- Foro o sección de consejos entre usuarios.
- Sistema de autenticación y roles (admin, usuario).
- API documentada con Swagger.

## 🧪 Pruebas

Se incluyen pruebas básicas con Jest para el backend y pruebas de integración/end-to-end para el frontend.

## 📄 Documentación

- Documentación técnica de la API disponible en la carpeta `docs/api`.
- Diagrama de base de datos en `docs/database`.
- Guías para contribuciones y desarrollo en `docs/guides`.

## 👨‍💻 Desarrolladores

- Oscar Alexander Cutiva Ramirez
- José Henry Olaya Casanova
