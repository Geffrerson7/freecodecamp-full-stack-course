Construir un reproductor multimedia
===================================

Aprobado

Construye una app que sea funcionalmente similar a este proyecto de ejemplo. Trata de no copiar el proyecto de ejemplo, dale tu propio estilo personal.

En las lecciones anteriores, se te presentó cómo trabajar con los elementos `audio` y `video`. En este laboratorio, construirás un reproductor multimedia que mostrará una pista de `audio` y un `video` con una transcripción.

Para el elemento `audio`, necesitará incluir un elemento `source` que se utiliza para especificar el medio que se está utilizando.

Aquí hay un ejemplo:

    <audio controls aria-label="descriptive label goes here">
      <source src="url-to-audio-goes-here" type="audio/mpeg">
    </audio>
    

El elemento `source` también se puede usar en el elemento `video` de esta manera:

    <video controls width="600" aria-label="descriptive label goes here">
      <source src="link-to-mp4-goes-here" type="video/mp4">
      <!-- Remaining code goes here -->  
    </video>
    

**Objetivo:** Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

**Historias de usuario:**

1.  Debería tener un elemento `h1` para el título principal de la página.
2.  Debería tener tres elementos `section`.
3.  Dentro del primer elemento `section`, debería tener un elemento `h2` para el título de la canción que se está reproduciendo.
4.  Debajo del elemento `h2`, debería tener un elemento `audio` con el atributo `controls` y un atributo `aria-label`.
5.  Dentro del elemento `audio`, debería tener un elemento `source` con un atributo `src` que apunte a un archivo de audio y un atributo `type`. Es libre de usar esta URL de audio si lo desea: `https://cdn.freecodecamp.org/curriculum/js-music-player/sailing-away.mp3`
6.  Dentro del segundo elemento `section`, debería tener un elemento `h2` para el título del video que se está reproduciendo.
7.  Debajo del elemento `h2`, debería tener un elemento `video` con atributos `controls`, `width` y un atributo `aria-label`.
8.  Dentro del elemento `video`, debes tener un elemento `source` con un atributo `src` que apunte a un archivo de video y un atributo `type`. Puedes usar esta URL de video si quieres: `https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.mp4`
9.  Debajo del elemento `source`, debes tener un elemento `track` con un atributo `src` que apunte a un archivo de subtítulos y un atributo `kind`, un atributo `srclang` y un atributo `label`. Puedes usar esta URL de subtítulos si quieres: `https://cdn.freecodecamp.org/curriculum/labs/what-is-the-map-method-and-how-does-it-work.vtt`
10.  Dentro del tercer elemento `section`, debes tener un elemento `h2` para el título de la sección, por ejemplo, "Transcript".
11.  Debajo del elemento `h2`, debería tener un elemento `p` con la transcripción del video.
