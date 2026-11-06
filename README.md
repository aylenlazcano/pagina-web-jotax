# Jotax Team — Muebles a medida

Sitio web de Jotax Team, taller de muebles a medida en melamina de La Plata. Proyecto final del curso de desarrollo web.

🔗 **Sitio publicado:** https://jotax-team.netlify.app

## Páginas
- **Inicio** — hero, primera visita con cota, trabajos, antes y después y preguntas frecuentes.
- **Nosotros** — Joel y Axel, su historia y lo que no negocian.
- **Servicios** — índice de rubros, cómo trabajamos y por qué melamina.
- **Trabajos** — galería por rubro, con tiras de fotos deslizables.
- **Contacto** — formulario y WhatsApp.

## Tecnologías
- HTML5 semántico, un `h1` por página, `title`, `description` y `keywords` propios y `alt` en todas las imágenes.
- SCSS con partials: variables, nesting, mixins con parámetros (`img-cover`, `columna-a-fila`, `rayado`), `@extend` con placeholders, maps y `@each` / `@for`.
- Bootstrap 5.3: navbar responsiva, acordeón (preguntas) y ScrollSpy (trabajos).
- Animaciones: `@keyframes`, `transition`, animaciones ligadas al scroll (`animation-timeline`) con `@property`, y AOS.
- Selectores modernos: `:has()`, `:target` y `:user-invalid`.
- Datos estructurados (JSON-LD) para el negocio y las preguntas frecuentes.
- Mobile-first, probado en celular, tablet y compu.

## Estructura
```
index.html
pages/          nosotros, servicios, portfolio, contacto
assets/images/  fotos del sitio
scss/
├── main.scss   solo @use
├── utilities/  variables y mixins
├── base/       etiquetas y tipografía
├── layout/     header, nav, footer, secciones
└── components/ una pieza por archivo
styles/         style.css compilado
```

## Cómo compilar
```
npm install
npm run sass
```
`npm run sass` queda mirando los cambios y compila `scss/main.scss` en `styles/style.css`.

## Deploy
Publicado en Netlify. El formulario de contacto usa Netlify Forms (`data-netlify="true"`), así que los mensajes llegan al panel de Netlify sin backend.

## Notas
Las imágenes son ilustrativas, generadas con IA, hasta tener fotos de los trabajos.

## Autora
Aylén Lazcano
