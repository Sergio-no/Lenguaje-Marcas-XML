# Ejercicio 2: Fichas

## Descripción
Este ejercicio define un esquema XML para validar un conjunto de fichas. Cada ficha tiene un código, un nombre, y atributos opcionales como número y letra.

## Archivos
- **fichas.xsd**: Contiene la definición del esquema XML para validar las fichas.
- **fichas.xml**: Ejemplo de un documento XML que cumple con el esquema.

## Uso
1. Utiliza el archivo `fichas.xsd` para validar documentos XML que contengan elementos `<fichas>`.
2. Asegúrate de que los valores de los elementos y atributos cumplan con las restricciones definidas en el esquema.

## Ejemplo de Uso
```xml
<fichas>
  <ficha numero="01" letra="Z">
    <codigo>11</codigo>
    <nombre>Ana Sanz Tin</nombre>
  </ficha>
</fichas>
```
