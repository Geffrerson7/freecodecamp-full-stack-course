Construir una página de pago
============================

Aprobado

Construye una app que sea funcionalmente similar a este proyecto de ejemplo. Trata de no copiar el proyecto de ejemplo, dale tu propio estilo personal.

**Objetivo:** Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

**Historias de usuario:**

1.  Debes tener un elemento `h1` con el texto `Checkout`.
2.  Debes tener dos elementos `section` inmediatamente después del elemento `h1`.
3.  Debes tener un elemento `h2` con el texto `Your Cart` dentro de la primera sección.
4.  Debes tener una imagen de un artículo en la primera sección con texto alternativo adecuado. Puedes usar esta imagen si lo deseas: `https://cdn.freecodecamp.org/curriculum/labs/cube.jpg`
5.  Debes tener un elemento `h2` con el texto `Payment Information` dentro de la segunda sección.
6.  Debes tener un elemento `form` dentro de la segunda sección.
7.  Debes tener un input con un `id` y `name` de `card-name`, y un `type` de `text` dentro de tu formulario y un `label` asociado a él.
8.  Debes tener un input con un `id` y `name` de `card-number`, y un `type` de `text` dentro de tu formulario y una `label` asociada a él.
9.  Debes tener al menos dos elementos `input` con el atributo `required`.
10.  Debes incluir un elemento `span` con el texto `*` y `aria-hidden` configurado en `true` dentro del elemento `label` para cada entrada requerida, de modo que los campos obligatorios estén indicados visualmente.
11.  Debes tener un elemento `p` con un texto de ayuda que explique el formato requerido del número de tarjeta, colocado inmediatamente después del campo de entrada del número de tarjeta. El `p` debe tener un `id` de `card-number-help` y ser referenciado por el campo de entrada del número de tarjeta usando `aria-describedby`.