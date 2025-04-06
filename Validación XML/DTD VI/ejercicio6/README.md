# Ejercicio 6: Futbol

## Descripción
Este ejercicio define un archivo XML que representa jugadores y equipos de fútbol. Los jugadores tienen atributos únicos como `nombre` y `codigo`, mientras que los equipos pueden referenciar a jugadores mediante el atributo `jugadores`.

## Estructura DTD
- **Elemento `futbol`**: Contiene una lista de elementos `jugador` y `equipo`.
- **Elemento `jugador`**: Es vacío y tiene los atributos:
  - `nombre` (NMTOKENS, obligatorio)
  - `codigo` (ID, obligatorio)
- **Elemento `equipo`**: Es vacío y tiene los atributos:
  - `nombre` (CDATA, obligatorio)
  - `jugadores` (IDREFS, opcional)

## Notas
- Los valores de `codigo` deben ser únicos.
- Los valores de `jugadores` deben referenciar códigos válidos de jugadores.
