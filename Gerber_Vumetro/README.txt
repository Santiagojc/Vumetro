Los ficheros .gpi y .dri los genera el Eagle automaticamente y solo son informativos.

El archivo .mill contiene los cortes de placa, tanto exterior (outline) como interior
(inline). (*Remarcar que la extensión .mill la creamos nosotros a propósito y no el Eagle. Las
extensiones se pueden crear con los nombres que queramos. Aunque es aconsejable dejar como están
las que se generan automáticamente) 

El resto de ficheros llevan una extensión asociada. Cada programa genera extensiones diferentes
para las diferentes capas. Estas extensiones son exclusivas de Eagle.

Extensiones asociadas a Eagle:

.sol -> Capa de cobre abajo
.cmp -> Capa de cobre arriba
.drd -> Taladros
.plc -> Leyenda de arriba
.sts -> Máscara antisoldante de abajo
.stc -> Máscara antisoldante de arriba

Para fabricar la pcb tan solo enviar el .zip a la empresa que los fabrica. En nuestro caso
la envíamos a AllPCB y no dió ningún problema.