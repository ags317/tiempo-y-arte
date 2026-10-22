# Tiempo & Arte

Sitio educativo sobre historia del arte, sus movimientos, artistas y obras destacadas.

## Entregable 2: estilización visual

- Cinco páginas HTML5 semánticas con navegación relativa.
- Hoja externa `styles/styles.css` enlazada desde las cinco páginas.
- Paleta de tres colores, tipografías Google Fonts y fondos personalizados.
- Jerarquía visual, contraste y estilos propios sin `!important` ni estilos inline.

Abrí `index.html` en el navegador. Las imágenes se consultan en Wikimedia Commons y requieren conexión a internet.


## Entregable 3 — Flexbox y Box Model
Se incorporó un reset universal, `box-sizing: border-box`, una barra de navegación Flexbox con `justify-content: space-between` y `align-items: center`, tarjetas con `gap` y `padding` mayor a 20px. Se trabajó especialmente en `index.html` y `pages/artistas.html`.


## Entregable 4: CSS Grid y responsividad

- `index.html`: presentación con `grid-template-areas`, tarjetas adaptables.
- `pages/artistas.html`: biografías en grilla responsive.
- Mobile-first: una columna por defecto, dos columnas desde 700 px y diseño desktop desde 1024 px.
- Conserva Flexbox para la barra de navegación y CSS del módulo 3.

Para comprobarlo, abrí las páginas en el navegador y usá las herramientas de desarrollo (F12) para simular pantallas de 375, 768 y 1280 px.
