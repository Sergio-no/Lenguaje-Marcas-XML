# Ejercicio 1: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar marcadores favoritos. Cada marcador contiene un nombre y una URI.

## Estructura del DTD
- **favoritos**: Elemento raíz que contiene uno o más elementos `marcador`.
- **marcador**: Contiene los elementos `nombre` y `uri`.
- **nombre**: Texto que representa el nombre del marcador.
- **uri**: Texto que representa la dirección URI del marcador.

## Problema
El archivo XML actual tiene un error en el elemento raíz, ya que utiliza `marcadores` en lugar de `favoritos`, lo que no cumple con la definición del DTD.
