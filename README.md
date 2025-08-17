El proyecto contiene dos partes:
1. El Código del Arduino Nano, es el código que se encarga del control del reloj de arena, este código tambien posee el control de la pantalla LCD.
2. El código de la ESP32, la cual contorla la caja fuerte en sí, la página web, el teclado, el sensor PIR, los botones y el servo motor.

Explicación general:
El proyecto es una caja fuerte automática, en esta podemos usar 4 modods distintos, el modo abrir automática, en el cual podemos setear el tiempo que 
queremos para que la caja feurte se abra, asímismo está el modo cerrar automático, el cual funciona exactamente como el modo anterior, pero este cierra la puerta,
tenemos el modod abrir con clave, el cual funciona poniendo la clave mediante el teclado, y por último está el modo cerra manual, el cual es un botón que cierra
la caja sin importar el modo que está. A parte, tenemos un sensor de movimiento el cual si no detecta movimiento, este no va a permitir usar los botones de modos,
esta información de tiempo será enviada en la pantalla LCD, la cual será donde veamos el modod que estamos, y el tiempo que seteamos.
Por último, tenemos un reloj de arena electrónico, hecho con matrices led, la cual mostrará exactamente un movimiento de un reloj de arena, contando con un giroscopio
para que los led se comporten como arena según la inclinacion de este, algo importante a resaltar, es que la velocidad de caída de la arena es proporcional
al tiempo seteado cuando ponemos un tiempo, si ponemos 10 segundos, esta arena caerá a esa velocidad, si ponemos 10 minutos, entonces caerá lento.

Video demostrativo: https://youtu.be/-O1jWoh8WFU

