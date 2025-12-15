# Proyecto Web Taller Mecánico

Este proyecto consiste en el desarrollo de una página web para un taller mecánico de coches, diseñada con un estilo moderno y profesional, inspirada en la estética de sitios web actuales.

## Descripción

La web ofrece información sobre los servicios del taller, detalles específicos sobre reparaciones comunes, y un formulario de contacto para los clientes. Ha sido desarrollada utilizando exclusivamente **HTML5 y CSS3**, sin el uso de frameworks ni librerías externas, cumpliendo con todos los requisitos técnicos y funcionales establecidos.

## Estructura del Proyecto

- `index.html`: Página de inicio con resumen y navegación.
- `pages/`: Carpeta que contiene las páginas secundarias.
  - `services.html`: Catálogo de servicios (Grid layout).
  - `detail-1.html`: Detalle de "Cambio de Aceite".
  - `detail-2.html`: Detalle de "Revisión de Frenos".
  - `contact.html`: Formulario de contacto.
- `css/`: Carpeta de estilos.
  - `style.css`: Hoja de estilos global.
- `img/`: Carpeta para imágenes (actualmente se usan imágenes externas de Unsplash).

## Elementos Originales y Características

Además de los requisitos básicos, se han incluido los siguientes elementos y características para mejorar la calidad y originalidad del proyecto:

1.  **Diseño "Dark Mode" en Header/Footer**: Siguiendo la referencia de *Barcelona Culinary Hub*, se ha implementado un diseño de alto contraste con cabecera y pie de página en negro y acentos en color dorado/naranja (#FFD700) para evocar la temática mecánica.
2.  **Validación Visual de Formularios**: Se ha implementado una validación avanzada utilizando solo CSS (`:valid`, `:invalid`, `:placeholder-shown`) que muestra iconos de check (verde) o error (rojo) dentro de los inputs mediante SVGs codificados en Data URIs, proporcionando feedback inmediato al usuario sin necesidad de JavaScript.
3.  **Animaciones y Transiciones**:
    - Efecto de "zoom" (`scale`) y sombra al pasar el ratón por las tarjetas de servicios.
    - Subrayado animado en los enlaces del menú de navegación.
    - Transiciones suaves en botones y campos de formulario.
4.  **Layout Responsive**: Uso de CSS Grid (`grid-template-columns: repeat(auto-fill, ...)`) para que las tarjetas de servicios se adapten automáticamente al ancho de la pantalla, y Flexbox para la estructura general.
5.  **Tablas Estilizadas**: Tablas con diseño "zebra" (filas alternas) y cabeceras destacadas para mejorar la legibilidad de los precios.
6.  **Incrustación de Video**: Se han incluido videos explicativos de YouTube en las páginas de detalle.
7.  **Badge de "Destacado"**: Implementación de una etiqueta visual para los servicios destacados utilizando pseudo-elementos CSS (`::before`).

## Autor

[Tu Nombre/Usuario]
