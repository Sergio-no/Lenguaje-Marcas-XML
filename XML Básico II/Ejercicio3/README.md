# Ejercicio 3: Receta de Cocina

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 23/03/2025  

## Descripción  
Este ejercicio consiste en un archivo XML que almacena una receta de cocina. Contiene información sobre los ingredientes y los pasos necesarios para preparar el plato.  

## Estructura del XML  
- `<recetas>`: Elemento raíz que contiene todas las recetas.  
- `<receta>`: Representa una receta específica con los siguientes subelementos:  
  - `<nombre>`: Nombre del plato.  
  - `<comensales>`: Número de personas para las que está pensada la receta.  
  - `<ingredientes>`: Lista de ingredientes necesarios.  
    - `<ingrediente>`: Cada ingrediente se indica en un nodo separado.  
  - `<proceso>`: Pasos detallados de preparación.  
    - `<paso>`: Cada paso de la receta en orden secuencial.  
