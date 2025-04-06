# Ejercicio 2: Inventores

Este archivo XML contiene una lista de inventores y sus inventos. Cada inventor incluye los siguientes atributos:

- **nombre**: El nombre del inventor.
- **invento**: El invento asociado al inventor.

El archivo utiliza una definición de tipo de documento (DTD) para validar su estructura. La DTD asegura que:

- El elemento raíz es `inventores`, que contiene una lista de elementos `inventor`.
- Cada elemento `inventor` tiene los atributos `nombre` y `invento`, ambos de tipo CDATA y obligatorios.
