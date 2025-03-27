# Ejercicio: Catálogo de Software Informático

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 27/03/2025  

## Descripción  
Este ejercicio consiste en la creación de un archivo XML que almacena información sobre diferentes tipos de software, incluyendo sistemas operativos y aplicaciones de oficina. El XML utiliza espacios de nombres para organizar mejor los diferentes tipos de software.  

## Estructura del XML  
- `<catalogo>`: Elemento raíz que contiene todos los software listados.  
- `<os:software>`: Representa un sistema operativo con los siguientes subelementos:  
  - `<os:nombre>`: Nombre del sistema operativo.  
  - `<os:version>`: Versión del sistema operativo.  
  - `<os:desarrollador>`: Empresa desarrolladora.  
  - `<os:url>`: Enlace al sitio oficial.  
- `<office:software>`: Representa un software de oficina con los siguientes subelementos:  
  - `<office:nombre>`: Nombre de la aplicación.  
  - `<office:version>`: Versión de la aplicación.  
  - `<office:desarrollador>`: Empresa desarrolladora.  
  - `<office:url>`: Enlace al sitio oficial.  