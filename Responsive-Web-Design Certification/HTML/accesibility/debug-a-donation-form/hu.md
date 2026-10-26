Depura un formulario de donación
================================

Aprobado

Una organización benéfica local ha creado un sitio web con un formulario de donación, pero hay varios problemas que necesitan ser corregidos. El formulario no es accesible y tiene algunos errores de sintaxis en HTML.

Tu trabajo es corregir todos los errores para que el formulario funcione correctamente y sea accesible para todos los usuarios. Completa los elementos en las historias de usuario a continuación y haz clic en "Check Your Code" para ver si corregiste todos los errores.

**Historias de usuario:**

1.  Los elementos `input` son elementos vacíos y no deben tener etiquetas de cierre. Elimina todas las etiquetas de cierre `</input>` del formulario.
2.  Agrega elementos `label` para cada campo de entrada del formulario para que los usuarios sepan para qué sirve cada campo. El texto del label debe coincidir con lo que actualmente está al lado de cada entrada.
3.  El tipo de entrada `Email Address:` debería ser un `email` en lugar de `text`.
4.  Debes asociar cada elemento `label` con su elemento `input` correspondiente usando el atributo `for` en el `label` y un atributo `id` coincidente en el `input`.
5.  Agrega el atributo `required` a los campos de entrada de texto, correo electrónico y número (pero no al checkbox ni al botón de envío) para asegurar que los usuarios completen la información requerida.