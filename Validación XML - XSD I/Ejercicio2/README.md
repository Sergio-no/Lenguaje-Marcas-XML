# Ejercicio 2

Este ejercicio valida un archivo XML que contiene una lista de fichas. Cada ficha tiene los siguientes elementos:

- **nombre**: Nombre de la persona (tipo `xs:string`).
- **edad**: Edad de la persona, que debe estar entre 1 y 130 años (tipo `xs:integer` con restricciones).
- **numero**: Atributo obligatorio que identifica la ficha (tipo `xs:integer`).

El esquema XSD asegura que las edades estén dentro del rango permitido y que los elementos estén correctamente definidos.
