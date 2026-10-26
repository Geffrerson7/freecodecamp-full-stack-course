Construye un Hub de eventos
===========================

Aprobado

Construye una app que sea funcionalmente similar a este proyecto de ejemplo. Trata de no copiar el proyecto de ejemplo, dale tu propio estilo personal.

En este laboratorio, utilizarás elementos semánticos de HTML para crear la estructura de una página web. Añadirás contenido e imágenes para que parezca un verdadero centro de eventos.

**Objetivo:** Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

**Historias de usuario:**

1.  Debes tener un elemento `header`, y debe ser el primer elemento dentro del `body`.
    
2.  Dentro del elemento `header`, debes tener un elemento `h1` que contenga el texto `Event Hub` y un elemento `nav`.
    
3.  Dentro del elemento `nav`, debes tener una lista desordenada de dos elementos que contengan enlaces a diferentes secciones de la página. El primer elemento debe tener el texto `Upcoming Events` y el segundo debe tener el texto `Past Events`.
    
4.  Cada enlace debe estar representado por un elemento `a` con un atributo `href` que enlace a la sección correspondiente de la página, `#upcoming-events` y `#past-events` respectivamente.
    
5.  Debes tener un elemento `main` que contenga las diferentes secciones de la página.
    
6.  Dentro del elemento `main`, debes tener dos elementos `section`.
    
7.  El primer elemento `section` debe tener un atributo `id` con el valor `upcoming-events`
    
8.  Dentro de la sección `#upcoming-events`, debes tener:
    
    *   Un elemento `h2` con el texto `Upcoming Events`.
    *   Dos elementos `article`. Cada artículo debe representar un evento, y debe tener:
        *   Un elemento `h3` para el título del evento.
        *   Un elemento `p` para la descripción del evento. Puedes añadir una fecha al final si lo deseas.
9.  El segundo elemento `section` debe tener un atributo `id` con el valor `past-events`.
    
10.  Dentro de la sección `#past-events`, debe tener:
    
    *   Un elemento `h2` con el texto `Past Events`.
    *   Dos elementos `article`. Cada elemento de artículo debe representar un evento pasado, y debe tener:
        *   Un elemento `h3` para el título del evento,
        *   Un elemento `p` para la descripción del evento. Puedes añadir una fecha al final si lo deseas.
        *   Un elemento de imagen con el atributo `src` apuntando a un archivo de imagen y el atributo `alt` con una descripción de la imagen.

**Nota:** Puede usar cualquier texto para las descripciones y fechas de los eventos. Puede usar las siguientes URL de imagen para las imágenes si lo desea:

*   `https://cdn.freecodecamp.org/curriculum/labs/past-event1.jpg`.
*   `https://cdn.freecodecamp.org/curriculum/labs/past-event2.jpg`.
