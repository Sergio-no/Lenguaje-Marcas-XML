# Ejercicio 6: Validación XML

## Descripción
Este ejercicio define una estructura XML para almacenar información sobre países, indicando si pertenecen a la Unión Europea o a la OTAN.

## Estructura del DTD
- **paises**: Elemento raíz que contiene uno o más elementos `pais`.
- **pais**: Contiene el elemento `nombre` y opcionalmente `unionEuropea` y `otan`.
- **nombre**: Texto que representa el nombre del país.
- **unionEuropea**: Elemento vacío que indica pertenencia a la Unión Europea.
- **otan**: Elemento vacío que indica pertenencia a la OTAN.

## Notas
El archivo XML actual cumple con la definición del DTD.
