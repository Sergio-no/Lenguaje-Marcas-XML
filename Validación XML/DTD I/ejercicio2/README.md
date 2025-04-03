# Ejercicio 2: Información de Liga de Jugadores

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información sobre una liga de jugadores en un archivo XML. Cada jugador tiene un nombre, apellidos, equipo (con ciudad y presidente), y edad.  

## Estructura del XML  
- `<liga>`: Elemento raíz que contiene todos los jugadores.  
- `<jugador>`: Representa un jugador con los siguientes subelementos:  
  - `<nombre>`: Nombre del jugador.  
  - `<apellidos>`: Apellidos del jugador.  
  - `<equipo>`: Contiene la información del equipo.  
    - `<ciudad>`: Ciudad del equipo.  
    - `<presidente>`: Contiene la información del presidente.  
      - `<nombrePresidente>`: Nombre del presidente.  
      - `<apellidosPresidente>`: Apellidos del presidente.  
  - `<edad>`: Edad del jugador.