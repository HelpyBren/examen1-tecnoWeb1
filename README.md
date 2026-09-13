# CV Interactivo — Brenett Eichentopf Sanchez

CV interactivo desarrollado para la materia Tecnologías Web I (SIS-214),
Primera Evaluación Práctica, Unidad I.

## Estructura del proyecto

```
cv-interactivo/
├── index.html          → Perfil / datos personales
├── formacion.html       → Formación académica
├── habilidades.html     → Habilidades técnicas
├── experiencia.html     → Proyectos
├── contacto.html        → Formulario de contacto
├── css/style.css        → Estilos globales (variables, layout, responsivo)
├── js/theme.js           → Modo claro/oscuro (persistente con localStorage)
├── js/validacion.js      → Validación del formulario de contacto
└── assets/images/        → Imágenes del sitio
```

## Cómo ejecutarlo localmente

1. Clona o descarga este repositorio.
2. Coloca tu foto de perfil en `assets/images/perfil.jpg`.
3. Abre `index.html` en tu navegador (no necesita servidor).

## Funcionalidades implementadas

- HTML5 semántico en las 5 páginas, con jerarquía de encabezados y navegación compartida.
- Diseño responsivo con CSS Grid y Flexbox, variables en `:root` y tema claro/oscuro.
- Modo claro/oscuro con JavaScript, con preferencia guardada en `localStorage`.
- Validación de formulario de contacto en el cliente (campos requeridos, formato de correo, longitud mínima de mensaje).

## Despliegue

Publicado con GitHub Pages desde la rama `main`.
