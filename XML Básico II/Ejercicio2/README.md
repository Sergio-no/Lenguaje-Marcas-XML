# Ejercicio 2: Información de Equipos de Fútbol

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 23/03/2025  

## Descripción  
Este ejercicio almacena información sobre equipos de fútbol en un archivo XML. Cada equipo tiene un nombre, una ciudad, un entrenador (opcional) y una lista de jugadores con sus posiciones y nacionalidades.  

## Estructura del XML  
- `<equipos>`: Elemento raíz que contiene todos los equipos.  
- `<equipo>`: Representa un equipo de fútbol con los siguientes subelementos:  
  - `<nombre>`: Nombre del equipo.  
  - `<ciudad>`: Ciudad del equipo.  
  - `<entrenador>`: Entrenador del equipo (puede estar vacío).  
  - `<jugadores>`: Contiene una lista de jugadores.  
    - `<jugador>`: Cada jugador tiene atributos como:  
      - `posición`: Indica si es defensa, portero, centrocampista, etc.  
      - `<nombre>`: Nombre del jugador.  
      - `<nacionalidad>`: Nacionalidad del jugador.  
