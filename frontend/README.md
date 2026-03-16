## Frontend – Proyecto Final Full Stack

Este es el frontend del **Proyecto Final Full Stack**, desarrollado con **React** y **Vite**.
Incluye autenticación de usuarios, gestión de publicaciones y vistas protegidas.

## Características

- Registro e inicio de sesión de usuarios
- Persistencia de sesión mediante contexto de autenticación
- Listado de publicaciones en formato galería
- Detalle de una publicación individual
- Creación de nuevas publicaciones
- Página de perfil de usuario
- Diseño responsive básico

## Requisitos

- Node.js (versión 18 o superior recomendada)
- npm (incluido con Node.js)

## Instalación

Desde la carpeta `frontend`:

```bash
npm install
```

## Scripts disponibles

- Iniciar el servidor de desarrollo:

	```bash
	npm run dev
	```

- Crear build de producción:

	```bash
	npm run build
	```

- Previsualizar la build de producción:

	```bash
	npm run preview
	```

## Configuración de la API (opcional)

Si el proyecto consume un backend externo, puedes definir la URL base de la API
mediante variables de entorno de Vite, por ejemplo:

```bash
VITE_API_URL=http://localhost:3000
```

(colócala en un archivo `.env` en la carpeta `frontend`, si la aplicación lo requiere).

## Estructura general

- Código fuente de React en `src/`
- Páginas principales (Home, Login, Registro, Perfil, etc.)
- Contexto de autenticación para proteger rutas y gestionar el usuario
- Estilos globales y componentes de layout reutilizables

## Desarrollo conjunto con el backend

Para trabajar en modo full stack:

1. Arranca el backend (Node/Express) en su carpeta correspondiente.
2. Arranca este frontend con `npm run dev`.
3. Asegúrate de que la URL configurada en la app (o en `VITE_API_URL`) apunte al backend en ejecución.
