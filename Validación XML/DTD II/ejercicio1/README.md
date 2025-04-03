# Ejercicio 1: Factura Electrónica

**Autor:** Sergio Negro Oliva  
**Curso:** 1ºDAM  
**Fecha:** 30/03/2025  

## Descripción  
Este ejercicio almacena información de una factura electrónica en un archivo XML. La factura contiene datos del emisor, del cliente y del detalle de los productos o servicios facturados.  

## Estructura del XML  
- `<factura>`: Elemento raíz que contiene la información de la factura.  
  - **Atributos**:  
    - `numero`: Número identificativo de la factura.  
    - `fecha`: Fecha de emisión de la factura.  
  - `<datos-emisor>`: Contiene la información del emisor de la factura.  
    - `<nombre>`: Nombre del emisor.  
    - `<cif>`: Código de Identificación Fiscal del emisor.  
    - `<telefono>`: Teléfono del emisor.  
  - `<datos-cliente>`: Contiene la información del cliente.  
    - `<nombre>`: Nombre del cliente.  
    - `<cif>`: Código de Identificación Fiscal del cliente.  
    - `<telefono>`: Teléfono del cliente.  
  - `<detalle-factura>`: Contiene el detalle de los productos o servicios facturados.  
    - **Atributos**:  
      - `importe`: Importe total de la factura.  
    - `<linea>`: Representa un producto o servicio facturado.  
      - **Atributos**:  
        - `codigo-articulo`: Código único del artículo.  
        - `tipo`: Tipo de artículo (Libro, DVD o Varios).  
      - `<descripcion>`: Descripción del artículo.  
      - `<cantidad>`: Cantidad facturada del artículo.  
      - `<pvp>`: Precio de venta por unidad del artículo.  
      - `<oferta>`: Indica si el artículo tiene una oferta (opcional). 