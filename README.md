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

## Layouts

Los [layouts](https://docs.astro.build/en/basics/layouts/) con componentes e astro usados para proporcionar una estructura de UI reutilizable, como un template. Los layouts se pueden usar para envolver páginas y componentes.

Un componente de diseño Astro típico proporciona a las páginas Astro, Markdown o MDX lo siguiente:

- Un shell de página (etiquetas `<html>`, `<head>` y `<body>`) 
- Un `<slot />` para especificar dónde se debe inyectar el contenido individual de la página.


> [!TIP]
> Una página muy util para ver templates de 404 es la siguiente [35+ HTML 404 Page Templates](https://dev.to/stackfindover/35-html-404-page-templates-5bge)

## View Transitions

Astro permite crear [transiciones de vista](https://docs.astro.build/en/guides/view-transitions/#adding-view-transitions-to-a-page) entre páginas. Las transiciones de vista son animaciones que se ejecutan al cambiar de una página a otra. Las transiciones de vista se pueden aplicar a todas las páginas o a páginas específicas.

Usando las transiciones de vista, podremos tener nuestro sitio web como si fuera una aplicación de una sola página (SPA).

## Desplegar Astro en GitHub Pages

Puedes desplegar un proyecto de [Astro en GitHub Pages](https://docs.astro.build/es/guides/deploy/github/) usando GitHub Actions para construir y desplegar tu proyecto automáticamente. Para hacer esto, tu código fuente debe estar alojado en GitHub.

Astro mantiene la acción oficial withastro/action para desplegar tu proyecto con muy poca configuración. Sigue las instrucciones a continuación para desplegar tu proyecto de Astro en GitHub Pages y consulta el README si necesitas más información.