# Registro pintacochinitos1

Formulario con el banner «Alas, sueños y un plan». Conserva nombre, correo, año de nacimiento y género.

Spreadsheet: https://docs.google.com/spreadsheets/d/1gFOvtvtW9n_GiDxCS6HKu5ftIODkviFiVYkxSB11_X8/edit
Destino: **Hoja 1**, `gid=0`.
Apps Script: https://script.google.com/u/0/home/projects/1-mDaQ64A8nV8mb7D_gb1fgOSxJ-7y_8oVzqhRLtzzblu19afOTKB9xua/edit

El código ya está guardado en el proyecto Registro Pintacochinitos1 y en `Código.gs` de esta carpeta. Las columnas respetan el orden existente: **Fecha y Hora | Nombre | Correo | Género | Año de nacimiento**. Los espacios al final de los encabezados se ignoran al validar.

Conexión activa: aplicación web publicada como versión 1, ejecutada como el propietario y accesible para cualquier usuario. La URL ya está configurada en `app.js`: https://script.google.com/macros/s/AKfycbx1Md-xh2kIV5W9U1o5JZrJCaNLO6gjtODcUIz6UQsBLJILjmYVYQ3jqfZ7IkvUW3_D/exec

Verificado el 6 de octubre de 2026: el formulario local envió correctamente y se comprobó el guardado en Hoja 1. Se conservan dos filas identificadas como PRUEBA CONEXIÓN PINTACOCHINITOS1 (filas 2 y 3): una desde el formulario y otra mediante POST directo para comprobar la respuesta del servicio. La publicación del sitio estático queda pendiente.

El envío usa `no-cors`: el navegador no puede confirmar que la fila se guardó. La pantalla muestra «Solicitud enviada»; verifica el guardado en la hoja. Cuando cambies el código, actualiza la versión de la implementación.