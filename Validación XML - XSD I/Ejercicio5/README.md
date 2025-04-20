# Ejercicio 5

Este ejercicio valida un archivo XML que contiene una lista de fichas. Cada ficha tiene los siguientes elementos:

- **nombre**: Nombre de la persona (tipo `xs:string`).
- **iniciales**: Tres letras mayúsculas que representan las iniciales del nombre (tipo restringido con patrón `[A-Z][A-Z][A-Z]`).
- **edad**: Edad de la persona (tipo `xs:integer`).

El esquema XSD asegura que las iniciales sean siempre mayúsculas y que los elementos estén correctamente definidos.
