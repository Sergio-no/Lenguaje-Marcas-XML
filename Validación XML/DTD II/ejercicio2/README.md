# Ejercicio 2: Equipos NBA

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información sobre equipos de la NBA en un archivo XML. Cada equipo contiene datos como el nombre, los títulos ganados, la posición en la conferencia y el quinteto titular.  

## Estructura del XML  
- `<EquiposNBA>`: Elemento raíz que contiene la información de los equipos.  
  - `<equipo>`: Representa un equipo de la NBA.  
    - **Atributos**:  
      - `conferencia`: Indica la conferencia a la que pertenece el equipo (Oeste o Este).  
    - `<nombre>`: Nombre del equipo.  
    - `<titulos>`: Número de títulos ganados por el equipo.  
    - `<posicion>`: Posición actual del equipo en la conferencia.  
    - `<quinteto>`: Nombres de los jugadores del quinteto titular.  
