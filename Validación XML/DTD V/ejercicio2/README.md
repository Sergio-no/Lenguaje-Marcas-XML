# Ejercicio 2: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar efemérides históricas. Cada efeméride contiene una fecha y un hecho.

## Estructura del DTD
- **efemerides**: Elemento raíz que contiene uno o más elementos `efemeride`.
- **efemeride**: Contiene los elementos `fecha` y `hecho`.
- **fecha**: Texto que representa la fecha del evento.
- **hecho**: Texto que describe el evento histórico.

## Problema
El archivo XML actual tiene un error en el comentario del DTD, que menciona incorrectamente que no se definió correctamente la estructura.
