# Bienvenido a mi proyecto para el curso Desarrollo Web de CoderHouse 💻

En esta oportunidad, la preentrega2 contiene:

-   Incorporacion de animaciones
-   Comportamiento responsivo mediante el uso de flexbox y bootstrap
-   Creacion de repositorio Github y publicacion del proyecto

## Responsive 🛠️

Para el comportamiento responsivo se utilizo el framework Bootstrap 4.4.1

```python
<!-- CDN de Bootstrap del CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
<!-- CDN de la librería de Jquery  -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"></script>
<!-- CDN de Bootstrap del JS -->
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
<!-- CDN de la librería de Popper  -->
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
```

## Sass 🖍️
Se implementa Sass y se modulariza el codigo del estilo en los partials:
1. components
    * `_buttons.scss`
    * `_jumbo.scss`

1. layout
    * `_footer.scss`
    * `_forms.scss`
    * `_header.scss`
    * `_hav.scss`

2. sections
    * `_general.scss`
    * `_index.scss`
    * `_inprogress.scss`

3. utilities
    * `_mixins.scss`
    * `_variables.scss`

Los mismos son importados en el archivo `_main.scss`
```css
@import "utilities/variables";
@import "utilities/mixins";

@import "base/reset";

@import "layout/footer";
@import "layout/forms";
@import "layout/header";
@import "layout/nav";

@import "sections/general";
@import "sections/index";
@import "sections/inprogress";

@import "components/buttons";
@import "components/jumbo";
```

## Animaciones 💫

Las animaciones se encuentran en los archivos:

-   `index.html`
-   `contacto.html`
-   `galeria.html`
-   `herramientas.html`
-   `herramientas1.html`

## Entrega 👨‍💻

**En el siguiente link podras ver el resultado al momento:** [Link a la demo](https://darzamendia.github.io/pre-entrega/). 🚀