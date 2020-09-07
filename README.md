# MENSAJE INVISIBLE

codifica y descodifica mensajes que no se pueden leer a simple vista.

## ¿Cómo funciona?

para codificar el mensaje lo que hace el script es:

1- obtener el código ascii de cada letra, por ejemplo A es 65. si este valor es mayor a 60 en el siguiente paso usaremos como caracter un punto (.) o en caso contrario un guión (-).

2- crar una cadena de texto donde se repite un caracter tantas veces como el valor del ascii en este caso 65 veces, aunque si es un valor mayor a 60, restaríamos 60 y en este caso se repetiría 5 veces, esto se ha hecho así para hacer el mensaje más corto.

3- cada línea representa una letra del mensaje.

en principio quería usar solo espacios, pero puede algunos formularios eliminen los espacios y sea imposible luego de descifrar el mensaje.

para descodificar hace el proceso inverso.

## Demo

[https://vivirenremoto.github.io/mensaje_invisible/](https://vivirenremoto.github.io/mensaje_invisible/)
