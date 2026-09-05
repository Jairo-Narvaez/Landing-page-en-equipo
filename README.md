# ☕ CaféTech - Landing Page en Equipo

Práctica de creación de archivos para trabajar en equipos colaborativos, usando Git, GitHub y ramas.

## 📋 Descripción del proyecto

Landing page ficticia para el negocio "CaféTech", desarrollada en equipo. Cada integrante fue responsable de una sección del sitio, trabajando en su propia rama de Git.

## 👥 Integrantes y secciones

| Integrante | Sección | Rama |
|---|---|---|
| Integrante 1 | Inicio | `inicio` |
| Integrante 2 | Servicios | `servicios` |
| Integrante 3 | Contacto | `seccion-contacto` |

## ⚙️ Cómo ejecutar

Abre el archivo `index.html` directamente en el navegador, o usa una extensión como Live Server en VS Code.

## 🌿 Flujo de trabajo con Git

1. Cada integrante creó su propia rama a partir de `main`:
2. Editó únicamente su sección asignada en `index.html`.
3. Guardó los cambios con conventional commits:
4. Subió su rama al repositorio remoto:
5. Se abrió un Pull Request hacia `main` para integrar los cambios.

## 📚 Conventional Commits usados

- `feat:` para contenido/funcionalidad nueva
- `docs:` para cambios en documentación
- `fix:` para corrección de errores





## Cambios - Integrante 1

- Se creó el archivo **style.css** (antes los estilos no existían como archivo separado).
- Se conectó el HTML al nuevo archivo CSS mediante `<link rel="stylesheet" href="style.css">`.
- Se agregaron imágenes de fondo (mediante URL) en las secciones:
  - **Inicio**: imagen con overlay oscuro para resaltar el título.
  - **Servicios**: imagen sin overlay, totalmente nítida.
  - **Contacto**: imagen con overlay oscuro para mantener legible el texto claro.
- Se ajustaron los niveles de opacidad de los overlays según la sección.