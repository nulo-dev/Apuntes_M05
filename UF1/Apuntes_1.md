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
  
  ### Modelo en V (II)
  
  - Modelo muy parecido al modelo en cascada.
  - Visión jerarquizada con distintos niveles.
  - Los niveles superiores indican mayor abstracción.
  - Los niveles inferiores indican mator nivel de detalle.
  - El resultado de una fase es la entrada de la siguiente fase.
  - Existen diferentes variantes con mayor o menor cantidad de actividades.
  
  ### Prototipos (I)
  
  - A menudo los requisitos no están especificados claramente:
      - Por no existir experiencia previa.
      - Por omisión o falta de concreción del usuario/cliente.
      
  ![Prototipos (I)](http://jamj2000.github.io/entornosdesarrollo/1/assets/prototipos.png "Prototipos (I)")
  
  ### Prototipos (II)
  
  - Proceso:
      - Se crea un prototipo durante la fase de análisis y es probado por el usuario/cliente para refinar los requisitos del software a desarrollar.
      - Se repite el paso anterior las veces necesarias.
      
  ### Prototipos (III)
  
  - Tipos de prototipos:
      - Prototipos rápidos
          - El prototipo puede estar desarrollado usando otro lenguaje y/o herramientas.
          - Finalmente el prototipo se desecha.
      - Prototipos evolutivos
          - El prototipo está diseñado en el mismo lenguaje y herramientas del proyecto.
          - El prototipo se usa como base para desarrollarel proyecto.
          
  ### Modelo en espiral (I)
  
  - Desarrollado por Boehm en 1988.
  - La actividad de ingeniería corresponde a las fases de los modelos clásicos: análisis, dieño, codificación, ...
  ![Modelo en espiral (I)](http://jamj2000.github.io/entornosdesarrollo/1/assets/espiral.png "Modelo en espiral (I)")
  
  ### Modelo en espiral (II) (Aplicado a la programación orientada a objetos)
  
  - En la actividad de ingeniería se da gran importancia a la reutilización de código.
  
  ![Modelo en espiral (II)](http://jamj2000.github.io/entornosdesarrollo/1/assets/espiral-poo.png "Modelo en espiral (II)")
  
  
  ### Metodologías ágiles (I)
  
  - Son métodos de ingeniería del software basados en el desarrollo iterativo e incremental.
  - Los requisitos y soluciones evolucionan con el tiempo según la necesidad del proyecto.
  - El trabajo es realizado mediante la colaboración de equipos auto-organizados y multidisciplinarios, inmersos en un proceso compartido de toma de decisiones a corto plazo.
  - Las metodologías más conocidas son:
      - Kanban
      - Scrum
      - XP (eXtreme Programming)
      
  ### Metodologías ágiles (II) (Manifiesto por el Desarrollo Ágil)
  
  - **Individuos e interacciones** sobre procesos y herramientas
  - **Software funcionando** sobre documentación extensiva
  - **Colaboración con el cliente** sobre negociación contractual
  - **Respuesta ante el cambio** sobre seguir un plan
  
  ### XP (Programación Extrema)
  
  - Simplicidad
  - Comunicación
  - Retroalimentación
  - Valentía o coraje
  - Respeto o humildad
---
###### © 2020 nulo-dev
