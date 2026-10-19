# Jotax Team — Muebles a medida

Sitio web de Jotax Team, taller de muebles a medida en melamina de La Plata.

🔗 **Sitio publicado:** https://aylenlazcano.github.io/pagina-web-jotax/

## Páginas
- Inicio
- Quiénes Somos
- Servicios
- Portfolio
- Contacto

## Tecnologías
- HTML5 semántico
- SCSS (Sass) con partials, variables, mixins y nesting — compilado a `styles/style.css`
- Flexbox y Grid (enfoque mobile-first)
- Bootstrap 5.3 (navbar responsive, carousel y grilla)

## Estructura SCSS
```
scss/
├── main.scss          # único punto de entrada (@use)
├── utilities/         # _variables.scss, _mixins.scss
├── base/              # _base.scss, _tipografia.scss
├── layout/            # _header.scss, _nav.scss, _footer.scss
└── components/        # _buttons, _cards, _textos, _hero, _cita, _bloques,
                       # _galerias, _formulario, _accordion, _carousel
```

Compilar: `npm install` y después `npm run sass` (queda mirando cambios).

## Responsive
Index, Quiénes Somos y Servicios están adaptadas a mobile y desktop.

## Autora
Aylén Lazcano