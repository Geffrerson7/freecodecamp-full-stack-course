Crea un Formulario de Encuesta
==============================

Aprobado

Construye una app que sea funcionalmente similar a este proyecto de ejemplo. Trata de no copiar el proyecto de ejemplo, dale tu propio estilo personal.

**Objetivo:** Cumplir con las historias de usuario a continuación y pasar todas las pruebas para completar el laboratorio.

**Historias de usuario:**

1.  Debe tener un título de página en in elemento `h1` con un `id` de `title`.
2.  Debes tener una explicación corta en un elemento `p` con un `id` de `description`.
3.  Debes tener un elemento `form` con un `id` de `survey-form`.
4.  Dentro del elemento de formulario debes tener un campo `input` requerido para ingresar tu nombre que tiene un `id` de `name` y un `type` de `text`.
5.  Dentro del elemento de formulario debes tener un campo `input` requerido para ingresar tu correo electrónico que tiene un `id` de `email`.
6.  Si ingresas un correo electrónico que no está formatado correctamente, deberías ver un error de validación HTML5.
7.  Dentro del elemento de formulario debes tener un campo `input` para ingresar un número que tiene un `id` de `number`.
8.  La entrada de números no debe aceptar caracteres no numéricos, ya sea impidiendo que los escribas o mostrando un error de validación HTML5 (dependiendo del navegador).
9.  Si ingresas números fuera del rango del input de número, que están definidos por los atributos `min` y `max`, deberías ver un error de validación HTML5.
10.  Para los campos de entrada de nombre, correo electrónico y número, debes tener elementos `label` correspondientes en el formulario que describan el propósito de cada campo con los siguientes ids: `name-label`, `email-label` y `number-label`.
11.  Para los campos de entrada de nombre, correo electrónico y número, debes tener un texto de marcador de posición que ofrece una descripción o instrucciones para cada campo.
12.  Dentro del elemento de formulario, debes tener un elemento desplegable `select` con un `id` de `dropdown` con al menos dos opciones para elegir.
13.  Dentro del elemento de formulario, puedes seleccionar una opción de un grupo de al menos dos botones de radio que son agrupados utilizando el atributo `name`.
14.  Dentro del elemento de formulario, puedes seleccionar varios campos en una serie de casillas de verificación, cada una debe tener un atributo `value`.
15.  Dentro del elemento de formulario, debes tener un `textarea` para comentarios adicionales.
16.  Dentro del elemento de formulario, debes tener un botón con `id` de `submit` para enviar todas las entradas.