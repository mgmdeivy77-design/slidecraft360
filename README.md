# SlideCraft AI — PWA Generador de Presentaciones

Aplicación Web Progresiva (PWA) optimizada para dispositivos móviles y escritorio que permite crear, editar, presentar y exportar presentaciones profesionales estilo PowerPoint (`.pptx`, `.html` interactivo y `.pdf`).

## Estructura del Repositorio

- `index.html`: Interfaz principal, motor de renderizado 16:9 anti-desbordamiento, gráficos SVG dinámicos y exportador `.pptx`.
- `manifest.json`: Configuración de instalación PWA (nombre, colores, iconos y modo *standalone*).
- `sw.js`: Service Worker para almacenamiento en caché y funcionamiento offline.
- `icon.svg`: Icono vectorial adaptable para Android, iOS y escritorio.

## Cómo desplegar en GitHub Pages

1. Crea un nuevo repositorio en tu cuenta de GitHub (por ejemplo, `slidecraft-ai`).
2. Sube todos los archivos de este ZIP (`index.html`, `manifest.json`, `sw.js`, `icon.svg`, `README.md`) a la raíz de la rama `main`.
3. Ve a **Settings → Pages** en tu repositorio.
4. En **Source**, selecciona `Deploy from a branch`, elige la rama `main` y la carpeta `/ (root)`, y haz clic en **Save**.
5. Abre la URL generada desde Chrome en tu celular y pulsa **Instalar App** (o *Añadir a pantalla de inicio*).
