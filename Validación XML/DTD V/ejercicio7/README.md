# Ejercicio 7: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar colores, especificando su nombre y código en formato RGB o CMYK.

## Estructura del DTD
- **colores**: Elemento raíz que contiene uno o más elementos `color`.
- **color**: Contiene los elementos `nombreSvg` y `codigo`.
- **nombreSvg**: Texto que representa el nombre del color en SVG.
- **codigo**: Contiene un único elemento `rgb` o `cmyk`.
- **rgb**: Texto que representa el código RGB del color.
- **cmyk**: Texto que representa el código CMYK del color.

## Notas
El archivo XML actual cumple con la definición del DTD.
