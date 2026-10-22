# Tiempo & Arte

**Un viaje por la historia del arte.**

Sitio educativo de cinco páginas sobre movimientos artísticos, artistas y obras destacadas, desarrollado como proyecto académico de desarrollo web.

## Sitio publicado

- [Ver Tiempo & Arte](https://ags317.github.io/tiempo-y-arte/)
- [Repositorio público](https://github.com/ags317/tiempo-y-arte)

> El enlace de GitHub Pages debe verificarse después de publicar los cambios.

## Páginas

- **Inicio:** presentación y galería de obras destacadas.
- **Movimientos:** recorrido por el Renacimiento, Barroco y otras corrientes.
- **Artistas:** biografías y aportes de pintores reconocidos.
- **Obras:** pinturas destacadas y sus autores.
- **Contacto:** presentación y participación en el proyecto educativo.

## Evolución: nueve entregables

| Módulo | Implementación |
|---|---|
| 1 | HTML5 semántico en cinco páginas, navegación e imágenes con epígrafes |
| 2 | CSS externo, tipografías y paleta de colores |
| 3 | Box Model y Flexbox para navegación y tarjetas |
| 4 | CSS Grid, `grid-template-areas` y media queries mobile-first |
| 5 | Bootstrap 5.3.3, navbar responsive, carruseles y estados interactivos |
| 6 | Git, rama `feature/responsive-final`, merge a `main` y GitHub Pages |
| 7 | Refactorización de CSS a SCSS con partials, variables y mixins |
| 8 | Sass avanzado, `@extend`, animaciones y AOS |
| 9 | SEO on-page, accesibilidad, metadatos y documentación final |

## Tecnologías

HTML5, CSS3, Sass/SCSS, Flexbox, CSS Grid, Bootstrap 5.3.3, AOS, Google Fonts, Git, GitHub y GitHub Pages.

## Estructura principal

```text
tiempo-y-arte/
├── index.html
├── pages/
│   ├── movimientos.html
│   ├── artistas.html
│   ├── obras.html
│   └── contacto.html
├── img/
│   └── FUENTES.md
├── scss/
│   ├── main.scss
│   ├── utilities/
│   ├── base/
│   ├── layout/
│   └── components/
├── styles/
│   └── style.css
├── package.json
└── README.md
```

## Cómo ejecutar

1. Cloná el repositorio y abrilo en VS Code.
2. Ejecutá `npm install` y `npm run build:css` para compilar el SCSS.
3. Abrí `index.html` en el navegador o publicá desde la rama `main` con GitHub Pages.

Se requiere conexión a internet para Bootstrap, Google Fonts, AOS y las imágenes externas.

## SEO y accesibilidad

- Un único `h1` por página y estructura semántica.
- `title` y `meta description` específicos en cada HTML.
- URLs canónicas para las cinco páginas.
- Textos alternativos en las imágenes y epígrafes con atribución.
- Enlace para saltar al contenido principal y estilos de foco visibles.
- Diseño adaptable y respeto por la preferencia de movimiento reducido.

## Fuentes de las imágenes

Consultá [`img/FUENTES.md`](img/FUENTES.md). Las obras se cargan mediante enlaces externos a Wikimedia Commons.

## Autoría

Proyecto académico de desarrollo web: **Tiempo & Arte**.
