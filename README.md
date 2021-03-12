# Modulo-Con-Comandos-seriales-Arduino-a-Matriz-led-8x8
Actividad 1.6_Modulo con comandos. Arquitectura de computadoras

Esta actividad consiste en mandar señales seriales mediante la terminal COM de arduino a traves de UART a una velocidad de 9600.

Mandando comandos de control como los siguientes:

  c! = siendo un comando de control para inicializar cualquier otra comando que nesecitemos mas adelante

  w! = Funcion write para mandar datos seriales a la memoria de arduino

  s! = Funcion show para mostrar los datos almacenados en la memoria

  f! = Funcion fps para reducir o incrementar la velocidad a la que pasa por los 4 modulos led 8x8

  b! = Funcion borrar, esta funcion se implementa para borrar las matrices y queden en blanco para ocupar despues

  p! = Funcion pausa, esta funcion nos sirve para pausar la animacion de lo que mandemos por el puerto serial en la posicion especificada

  l! = Funcion logo, esta funcion sirve para mandar un logotipo o animacion a las matrices led (space invaders)

  d! = Funcion data memory para mostrar en la terminal lo que tenemos en la memoria del arduino

  i! = Funcion intensidad, esta funcion nos permite modificar la intensidad de brillo de las matrices led (mayor luz o menor luz en los led)

