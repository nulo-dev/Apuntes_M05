# ENTORNOS DE DESARROLLO

####  FRAMEWORK

Un framework es un marco de trabajo que permite unificar el proceso de desarrollo entre desarrolladores y esta compuesto por:


- Un conjunto de las mejores prácticas y suposiciones
- Herramientas mas comunes
- Bibliotecas


------------




## PRUEBAS

####  OBJETIVOS DE LAS PRUEBAS

- Una buena prueba tiene dos objetivos:
1.  Probar si el software no hace lo que debe hacer.
2.  Probar si el software hace lo que no debe hacer.

#### FORMA DE LAS PRUEBAS

- **Pruebas dinámicas:** Se utilizan para revisar como se comporta la aplicacion cuando esta en ejecucion.

- **Pruebas estáticas** Se utilizan para revisar el codigo linea a linea (se revisa el codigo fuente sin ejecutar la aplicación)


#### ESTRATEGIAS DE PRUEBA

- **Caja blanca:** 
	- Se examina el código fuente y su ejecución.
	- Se comprueban los flujos de ejecución dentro de cada unidad (funciones,clases,modulos)
	- Cobertura de código
	- Prueba de bucles

- **Caja negra:** 
	- Se estudia la aplicacion desde fuera.
	- No se tienen en cuenta los detalles internos.
	- Se estudian las salidas.
	- Valores límite


![Estrategias de pruebas (caja blanca y caja negra)](http://jamj2000.github.io/entornosdesarrollo/3/assets/caja_blanca-caja_negra.png "Estrategias de pruebas (caja blanca y caja negra)")

> En la caja blanca observamos las funciones que utiliza el programa para dar la salida final y en cambio en la caja negra solo observamos la entrada y la salida sin importar como funcione la aplicacion por dentro.

####  TIPOS DE PRUEBAS

- **Funcionales:** Evaluan el cumplimiento de los requisitos.
	- Pruebas unitarias.
	- Pruebas del sistema.
	- Pruebas de aceptación.
	- ...
- **No funcionales:** Evaluan aspecto adicionales como rendimiento,seguridad,estructura, ...
	- Pruebas de usabilidad
	- Pruebas de rendimiento
	- Pruebas de stress
	- Pruebas de seguridad
	- ...

#### MECANISMOS DE PRUEBA

- Manual
	- Mediante pruebas realizadas por personal de la empresa o externo.
- Automático
	- Mediante software que ejcuta código automatizado comparando los resultados obtenidos con los resultados esperados.


#### COBERTURA DEL CÓDIGO

Es una medida (como una barra de carga) que indica cuanto porcentaje de codigo ha ejecutado satisfactoriamente, si el porcentaje es 100% signfiica que el codigo que ha ejecutado por completo, si el porcentaje es menor a 100% significa que el codigo no se ha ejecutado por completo y habria que revisar que le sucede para conseguir que el codigo se ejecute al 100%

### CALIDAD

En el apartado de calidad hacemos mediciones de la calidad del producto

#### CALIDAD DEL PROCESO/PRODUCTO (QA/QC)

QA: Garantiza la calidad de los productos mediante actividades cuando el producto se esta desarrollando.
QC: Garantiza la calidad de los productos mediante actividades que se centran en identificar defectos en los productos reales.


#### FACTORES DE CALIDAD

Hay 11 factores de calidad segun el modelo de McCall y se agrupan en 3 ambitos los cuales mencionaremos ahora.

##### OPERACIÓN DEL PRODUCTO

- Corrección
- Fiabilidad
- Eficiencia
- Seguridad
- Facilidad de uso

##### REVISIÓN DEL PRODUCTO

- Mantenibilidad
- Flexibilidad
- Facilidad de prueba

##### TRANSICIÓN DEL PRODUCTO

- Portabilidad
- Reusabilidad
- Interoperatividad

------------



> **&copy; nulo-dev**
