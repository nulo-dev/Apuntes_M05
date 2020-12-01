# Elementos del desarrollo de software
---

# Introducción

## Tipos de Software

  - **De sistema** (Sistema operativo, dirvers)
  - **De aplicacion** (Suite ofimática, Navegador, Edición de imagen, ...)
  - **De desarrollo** (Editores, compiladores, interpretes, ...)

## Relación Hardware-Software

  - **Disco duro**: Almacena de forma permanente los datos.
  - **Memoria RAM**: Almacena de forma temporal el código binario de los archivos.
  - **CPU**: Lee y ejecuta instrucciones almacenadas en memoria RAM.
  - **E/S**: Recoge datos desde la entrada(*Ejemplo: Un raton*), se muestran los resultados,se leen/guardan en el disco,...

## Códigos fuente, objeto y ejecutable
 
 - **Código fuente**: Archivo de texto legible escrito en un lenguaje de programación.
 - **Código objeto**: Archivo binario no ejecutable.
 - **Código ejecutable**: Archivo binario ejecutable

# Ciclo de vida del software
---

## Desarrollo de software
\
Fases Principales
 - [**Analisis**](https://github.com/nulo-dev/Apuntes_M05/blob/main/UF1/Apuntes_1.md#analisis)
 - [**Diseño**](https://github.com/nulo-dev/Apuntes_M05/blob/main/UF1/Apuntes_1.md#dise%C3%B1o)
 - [**Codificación**](https://github.com/nulo-dev/Apuntes_M05/blob/main/UF1/Apuntes_1.md#codificaci%C3%B3n)
 - [**Pruebas**](https://github.com/nulo-dev/Apuntes_M05/blob/main/UF1/Apuntes_1.md#pruebas)
 - [**Mantenimiento**](https://github.com/nulo-dev/Apuntes_M05/blob/main/UF1/Apuntes_1.md#mantenimiento)

### Analisis

 - Se determina las necesidades de los clientes i los requisitos que debe cumplir.
 - La especificación de requisitos debe:
    - Ser completa y sin omisiones
    - Ser concisa y sin trivialidades
    - Evitar ambigüedades
    - Evitar detalles de diseño o implementación
    - Ser entendible por el cliente
    - Separar requisitos funcionales y no funcionales
    - Dividir y jerarquizar el modelo
    - Fijar criterios de validación

### Diseño

 - Se organiza el sistema en elementos que pueden ser desarrollados por separado.
 - Las actividades habituales son las siguientes:
    - Diseño arquitectónico
    - Diseño detallado
    - Diseño de datos
    - Diseño de interfaz

### Codificación

 - Se escribe el código fuente de cada componente.
 - Pueden utilizarse distintos lenguajes informáticos:
    -  **Lenguajes de programación**: C, C++, Java, Javascript, ...
    -  **Lenguajes de otro tipo**: HTML, XML, JSON, ...

### Pruebas

 - El principal objetivo de las pruebas debe ser conseguir que el programa funcione incorrectamente y que se descubran defectos.
 - Deberemos someter al programa al máximo número de situaciones diferentes.
 
### Mantenimiento

 - Se realizan cambios (fallos encontrados en las pruebas, mejoras, etc).
 - Tipos de mantenimiento:
    - **Correctivo**: se corrigen defectos.
    - **Perfectivo**: se mejora la funcionalidad.
    - **Evolutivo**: se añade funcionalidades nuevas.
    - **Adaptativo**: se adapta a nuevos entornos.

### Resultado tras cada fase (I)

 - Ingeniería de sistemas: **Especificación del sistema**
 - Análisis: **Especificación de requisitos del software**
 - Diseño arquitectónico: **Documento de arquitectura del software**
 - Diseño detallado: **Especificación de módulos y funciones**
 - Codificación: **Código fuente**

 ### Resultado tras cada fase (II)

 - Pruebas de unidades: **Módulos utilizables**
 - Pruebas de integración: **Sistema utilizable**
 - Pruebas del sistema: **Sistema aceptado**
 - Documentación: **Documentación técnica y de usuario**
 - Mantenimiento: **Informes de errores y control de cambios**
  
 ## Modelos de desarrollo de software

  - Modelos clásicos (predictivos)
      - Modelo en cascada
      - Modelo en V
  - Modelos de construcción de prototipos
  - Modelos evolutivos o incrementales
      - Modelo en espiral (iterativos)
      - Metodologías ágiles (adaptativas)
      
  ### Modelo en cascada (I)
  
  ![Model en Cascada (I)](http://jamj2000.github.io/entornosdesarrollo/1/assets/cascada.png "Model en Cascada (I)")
  
  ### Modelo en cascada (II)
  
  - Modelo de mayor antigüedad.
  - Identificada las fases principales del desarrollo software.
  - Las fases han de realizarse en el orden indicado.
  - El resultado de una fase es la entrada de la siguiente fase.
  - Es un modelo bastante rígido que se adapta mal al cambio continuo de especificaciones.
  - Existen diferentes variantes con mayor o menor cantidad de actividades.
  
  ### Modelo en V (I)
  
  ![Model en V (I)](http://jamj2000.github.io/entornosdesarrollo/1/assets/v.png "Model en V (I)")
---
###### © 2020 nulo-dev
