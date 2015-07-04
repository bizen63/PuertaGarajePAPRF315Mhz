# PuertaGarajePAPRF315Mhz
Automatización de una puerta de garaje con Arduino, utilizando un mando
a distancia por RF (315Mhz) y un motor paso a paso. Utiliza finales de
carrera arriba y abajo y un detector de presencia en puerta. Es un
proyecto ideal para implementar con fines didácticos. El cableado y la
lista de materiales se deducen de los comentarios del programa.
OJO, el esquema de conexiones está realizado con Arduino Nano y un servomotor, aquí se ha utilizado Arduino Uno y un motor PAP, con su controlador, como puede leerse en los comentarios del programa, donde está toda la información necesaria.
El programa emplea las interrupciones 0 y 1 para activar los programas que suben y bajan la puerta, la interrupción 0 se corresponde con el pin D0 del receptor del mando RF y la interrupción 1 con el pin D1.
