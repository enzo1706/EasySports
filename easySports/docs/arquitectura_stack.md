# Arquitectura y Stack Tecnológico

## Frontend
- **Framework:** React con TypeScript.
- **Arquitectura UI:** Atomic Design y Patrón Container-Presentational (¡separá la lógica de negocio de la vista de una vez por todas, fundamental!).
- **Estado:** GPX-Store o Redux (para la sesión y datos globales del equipo).
- **Estilos:** TailwindCSS.

## Backend
- **Framework:** Node.js con Express y TypeScript.
- **Arquitectura:** Clean Architecture / Hexagonal (Dominio aislado, infraestructura en adaptadores).
- **Base de Datos:** PostgreSQL (Relacional, ideal para manejar transacciones y pagos).

## Infraestructura
- **Contenedores:** Docker.
- **Despliegue:** Frontend en Vercel, Backend y DB en Railway/Render.
