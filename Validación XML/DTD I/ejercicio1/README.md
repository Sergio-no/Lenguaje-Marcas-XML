# Ejercicio 1: Información de Biblioteca

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información sobre libros en una biblioteca dentro de un archivo XML. Cada libro tiene un título, una editorial, un autor (con nombre y apellidos) y un número de páginas.  

## Estructura del XML  
- `<biblioteca>`: Elemento raíz que contiene todos los libros.  
- `<libro>`: Representa un libro con los siguientes subelementos:  
  - `<titulo>`: Título del libro.  
  - `<editorial>`: Nombre de la editorial.  
  - `<autor>`: Contiene la información del autor.  
    - `<nombre>`: Nombre del autor.  
    - `<apellidos>`: Apellidos del autor.  
  - `<num_paginas>`: Número de páginas del libro.  