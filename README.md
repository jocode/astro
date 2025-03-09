# Astro

Astro es un framework de desarrollo web que permite crear sitios web basados en contenido (Por ejemplo blogs o e-commerce). Astro es un generador de sitios web estáticos, lo que significa que no requiere de un servidor para funcionar.

Astro va a optimizar tu sitio web para que sea rápido y seguro. Astro va a generar un sitio web estático que se puede servir desde cualquier servidor web.

## Instalación

Para instalar Astro necesitas tener instalado Node.js y npm. Puedes instalar Astro con el siguiente comando:

```bash
npm create astro@latest
```


## Directorios y archivos

Astro tiene una estructura de directorios y archivos que se generan automáticamente al crear un nuevo proyecto. La estructura de directorios y archivos es la siguiente:

- `src/`: El código fuente de tu sitio web. (componentes, páginas, estilos, etc.)
- `public/`: Recursos estáticos, assets no procesados (imágenes, fuentes, etc.)
- `package.json`: El manifiesto de tu proyecto.
- `astro.config.mjs`: La configuración de Astro.
- `tsconfig.json`: La configuración de TypeScript.
- `src/content/`: Contenido de tu sitio web (archivos Markdown, JSON, etc.)
- `src/actions/`: Acciones de tu sitio web (funciones Lambda, etc.)