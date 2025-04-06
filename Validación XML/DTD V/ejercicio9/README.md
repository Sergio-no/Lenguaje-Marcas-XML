# Ejercicio 9: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar mensajes. Cada mensaje contiene información sobre el remitente, destinatario, hora y texto.

## Estructura del DTD
- **mensajes**: Elemento raíz que contiene uno o más elementos `mensaje`.
- **mensaje**: Contiene los elementos `de`, `para`, `hora` y `texto`.
- **de**: Texto que representa el remitente del mensaje.
- **para**: Texto que representa el destinatario del mensaje.
- **hora**: Texto que representa la fecha y hora del mensaje.
- **texto**: Puede contener texto o elementos `strong`.
- **strong**: Texto que representa contenido destacado.

## Notas
El archivo XML actual cumple con la definición del DTD.
