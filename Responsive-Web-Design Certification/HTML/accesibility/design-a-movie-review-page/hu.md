Diseñar una página de reseña de películas
=========================================

Aprobado

Construye una app que sea funcionalmente similar a este proyecto de ejemplo. Trata de no copiar el proyecto de ejemplo, dale tu propio estilo personal.

**Objetivo:** Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

**Historias de usuario:**

1.  Debes tener un elemento `main`.
2.  Dentro del elemento `main`, debes tener un elemento `h1` para el título de la película.
3.  Debajo del elemento `h1`, debes tener un elemento `img` que muestre la portada de la película. Tu elemento `img` debe tener un texto `alt` descriptivo que describa la imagen. Puedes usar la siguiente imagen si quieres: `https://cdn.freecodecamp.org/curriculum/labs/rise-beyond-2.png`.
4.  Debes tener un elemento `p` que contenga una breve descripción de la película.
5.  Debes tener otro elemento `p` para mostrar la calificación de la película. Dentro de este, debes tener estos elementos en el orden listado:
    *   Un elemento `b` con el texto `Movie Rating:`.
    *   Un elemento `span` con un atributo `aria-hidden` establecido en `true` que contenga una representación visual de la calificación usando estrellas `⭐⭐⭐⭐⭐⭐⭐⭐⭐☆`.
    *   Un valor numérico, que representa la calificación, entre paréntesis (por ejemplo, `9.2/10`) después del span.
6.  Debes tener un elemento `h2` con el texto `Cast Members`.
7.  Debes tener un elemento `ul`.
8.  Dentro del elemento `ul`, debes tener múltiples elementos `li`, cada uno conteniendo un elemento `b` para el nombre del actor seguido del nombre del personaje correspondiente precedido por el texto `as`. (por ejemplo, `James Holloway as Ethan Carter`).