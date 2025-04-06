# Ejercicio 5: Futbol

## Descripción
Este ejercicio define un archivo XML que representa una lista de jugadores de fútbol. Cada jugador tiene atributos únicos como `nombre` y `codigo`.

## Estructura DTD
- **Elemento `futbol`**: Contiene una lista de elementos `jugador`.
- **Elemento `jugador`**: Es vacío y tiene los atributos:
  - `nombre` (NMTOKENS, obligatorio)
  - `codigo` (ID, obligatorio)

## Notas
- El atributo `nombre` debe ser de tipo `NMTOKENS`, por lo que no puede contener espacios.
- Los valores de `codigo` deben ser únicos.
