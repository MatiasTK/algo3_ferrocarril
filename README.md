# El Ferrocarril

Una empresa de servicios ferroviarios europea define los siguientes conceptos:

**Tramo:** es un recorrido entre dos ciudades sin cambio de tren, con o sin paradas intermedias. Cada
tramo tiene un precio dependiendo del tipo de tren y categoría de pasaje (tipo: tren de alta
velocidad, tren nocturno, tren común, etc.; categoría: primera, segunda).

**Servicio adicional:** es un servicio, no gratuito y optativo, que se puede adquirir junto con un
tramo, pero que no se vende separado; por ejemplo: “cucheta coche dormitorio”, “cucheta en
compartimiento privado”, “cena a bordo”. No se puede combinar cualquier ítem con cualquier
adicional; por ejemplo, sólo se puede contratar cuchetas en trenes nocturnos.

**Pasaje:** es un derecho de viaje para uno o más pasajeros, para un tramo, o un tramo más uno o
más adicionales. Su precio se calcula como suma de los precios de los componentes, por la
cantidad de pasajeros. Todos los pasajeros viajan en el mismo tren y en la misma categoría.

**Viaje promocional:** es un conjunto de pasajes, que pueden incluir varios tramos y que tienen un
precio promocional en conjunto; por ejemplo, puede haber un precio especial para la “5 pasajes
entre París y Marsella, en TGV, segunda clase, viajando con cambio de tren en Lyon”. Los viajes
promocionales tienen una vigencia: permanentes, por una estación del año, por día se semana o
fin de semana.

Se debe:

- Modelar en UML (diagrama de clases) el problema recién descripto.
- Modelar en UML (2 diagramas de secuencia) el cálculo del precio de un pasaje y el de un
  viaje promocional.
- Escriba todas las pruebas automatizadas necesarias para probar el comportamiento
  modelado en el diagrama de secuencia del viaje promocional, usando SUnit.
- Escriba el código Smalltalk que haga funcionar las pruebas del punto anterior, pero sin
  escribir nada de los métodos de otras clases (dicho de otra manera, los métodos de otras
  clases debe suponerlos implementados).
