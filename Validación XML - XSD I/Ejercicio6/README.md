# Ejercicio 6

Este ejercicio valida un archivo XML que contiene una lista de fichas. Cada ficha tiene los siguientes elementos:

- **nombre**: Nombre de la persona (tipo `xs:string`).
- **iniciales**: Tres letras (mayúsculas o minúsculas) que representan las iniciales del nombre (tipo reutilizable `tipoIniciales`).
- **edad**: Edad de la persona (tipo `xs:integer`).
- **iniciales-al-reves**: Las iniciales del nombre en orden inverso (tipo reutilizable `tipoIniciales`).

El esquema XSD utiliza un tipo simple reutilizable para definir las iniciales y asegura que los elementos estén correctamente definidos.
