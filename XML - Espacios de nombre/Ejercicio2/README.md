# Ejercicio: Corrección de Conflictos Información de Libros

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 27/03/2025  

## Descripción  
Este ejercicio consiste en la creación de un archivo XHTML que almacena reseñas de libros utilizando un espacio de nombres para la información bibliográfica. La estructura permite organizar datos como el título, el autor, el precio, el número de páginas y la fecha de publicación.

## Estructura del XHTML  
- `<html>`: Elemento raíz que define el documento XHTML.  
- `<head>`: Contiene los metadatos y el título de la página.  
- `<body>`: Cuerpo principal del documento.  
  - `<book:bookreview>`: Sección que representa la reseña de un libro con los siguientes subelementos:  
    - `<book:title>`: Título del libro.  
    - `<table>`: Tabla que organiza la información clave del libro:  
      - `<book:author>`: Autor del libro.  
      - `<book:price>`: Precio del libro.  
      - `<book:pages>`: Número de páginas.  
      - `<book:date>`: Fecha de publicación.  