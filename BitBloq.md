# Programar Para Educar

## Curso del CEP de Granada

## Enero de 2016

[Calendario](./Indice.md)

### José Antonio Vacas @javacasm

![CCbySA](imagenes/CCbySQ_88x31.png)


# Programando con Bitbloq

### http://bitbloq.bq.com


Bitbloq es un entorno de programación visual que nos permite hacer pogramas para Arduino sin tener conocimientos de programación.

Un programa estará formado un conjunto de bloques que encajan entre sí.

Los bloques están agrupados en familias, cada una de ellas con un color concreto.
# Minicurso Bitbloq

Bitbloq es un entorno de programación visual que nos permite crear programas para Arduino y placas compatibles y transferir los mismos a las placas de una forma sencilla.

Podemos acceder directamente desde su web  http://bitbloq.bq.com/
(Pudiera ocurrir que algunos vídeos se usa la versión anterior, que era la recomendada hasta hace poco ...)

Funciona mejor con Chrome en todos los sistemas operativos, y al usarlo te dirá si necesitas drivers o instalar algún complemento en tu sistema

A lo largo de estos vídeos veremos algunas de sus características más importantes.

## Introducción a la programacion con bitbloq:

[[vídeo]](https://youtu.be/rOdMRhhQTUs) [[ejemplo Parpadeo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/blob/master/bitbloq/1.%20parpadeo.json)

![parpadeo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/1%20parpadeo.png)

Bitbloq es un entorno de programación visual por bloques que nos permite programar nuestra placa arduino o compatible de forma sencilla, evitando la complejidad de las sentencias C++

Además nos permite programar nuestro arduino sin instalar (practicamente) nada en nuestro ordenador

Empezaremos seleccionando el tipo de placa Arduino que vamos a usar y a continuación añadiremos el hardware que usemos conectándolo a las patillas correspondientes.


### Ver código C++ de un programa bitbloq:  
[[video]](https://youtu.be/cg1YNVSprdo)

Desde bitbloq siempre podemos ver el codigo Arduino generado. De momento no podemos modificar este código pero si copiarlo y llevarlo al IDE de arduino


### Transfiriendo el programa bitbloq a Arduino
[[vídeo]](https://youtu.be/95oW-hOX9pc)

Bitbloq nos permite programar nuestro arduino sin instalar (practicamente) nada en nuestro ordenador. Sólo tenemos que pulsar sobre el botón cargar lo que hace que se compile el código, se detecte la placa y se envíe el programa a naestro Arduino


Para aprender las funciones de pin en bitbloq  
[[vídeo]](http://youtu.be/zKs0-vwoxMM)

Las funciones de pin son las distintas formas que tenemos de manejar los pines de arduino. Tenemos las mismas sentencias que en arduino (en el menú Funciones de Pin): DigitalWrite, AnalogWrite, DigitalRead y AnalogRead. También podemos usarlas si utilizamos un bloque ZUM o octopus correspondiente. ????

## Sentencias de control

[[video]](https://youtu.be/dakh7MTxpBg)

Las sentencias de control son aquellas que nos permite modificar el orden o el modo en el que se ejecutan los bloques de nuestro programa

### Variables

Para utilizar las sentencias de control necesitaremos el concepto de variables: que no es otra cosa que un lugar donde almacenar un valor que puede se modificar si así lo queremos

[[video]](https://youtu.be/Os-8oHBKsQU)

Con las variables podemos realizar operaciones matemáticas

[[video]](https://youtu.be/nvRUCZERScE)  [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/operaciones%20variables.json)

![ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/operaciones%20variables.png)

### Bucle **for**
[[vídeo]](https://youtu.be/mIAgTdc4oC8) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/bucle%20for.json)

![bucle for](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/bucle%20for.png)

El bucle **for** permite repetir un conjunto de pasos un número de veces determinado.
Necesitamos  declarar una variables que actuará como contador y definir el valor inicial que tendrá la variable y el final, realizándose tantos como pasos como valores enteros haya entre ambas.

### Bucle **while**
[[vídeo]](https://youtu.be/RVcaaz1NYjk) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/bucle%20while.json)

![bucle while](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/bucle%20mientras.png)

Usaremos la sentencia de control **while** para los bucles donde el número de veces que se repite no está definido desde el principio

### Bloque **if** : sentencias condicionales
[[vídeo]](https://youtu.be/RTtn_77pZY4	) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/condiconales.json)

![condicional](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/condicionales.png)

Las sentencias condicionales permiten ejecutar un código y otro según se cumpla o no una determinada condición. Esta condición será una validación que definiremos con operandos.

Podemos hacer que en caso de que se cumpla se ejecute un código (es el bloque if) y en caso de que no se cumpla la condición se ejecute otro (bloque else). Veamos un ejemplo

[[video]](https://youtu.be/-f_htl5TQN8)[[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/condicional%20compleja.json)

![ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/concional%20compleja.png)

### Condicionales complejas
[[vídeo]](http://youtu.be/en_Y-_wVyO0) [[ejemplo]](./ejemplosBitbloq/condiciones_if.xml)

![Condiciones_lógicas](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/concional%20compleja.png)

La condición que determina si se ejecuta un bloque u otro o si salimos de un bloque while puede contener varias comprobaciones.

Entre estas condiciones utilizaremos operadores lógicos que pueden ser AND o OR

* Estas condiciones se tendrán que cumplir todas en el caso del operador AND

* Con que se cumpla una de elllas se dará por válida toda la condición


## Envío de datos al PC:
[[vídeo]](https://youtu.be/hy9t76RLeBU) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/comunicacion%20serie.json)

![serial](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/comunicacion%20serie.png)

Podemos enviar contenidos entre nuestra placa y el PC usando las sentencias de comunicaciones. Usaremos print para enviar algo (puede ser el valor de una variable o un texto) al pc o println para enviar y pasar a la siguiente línea.

## Variables locales vs Variables globales

[vídeo](https://youtu.be/U3ulo7rAE58) [ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/variables%20globales.json)

![ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/variables%20globales.png)

Podemos definir variables locales o globales. Una variable global estará definida y por tanto mantendrá su valor en todo el programa, mientras que una variable local solo se definirá donde se haya declarado.

Las variables globales mantienen su valor entre las distintas iteraciones que se realizan del programa.

## Ejemplo de bucle sin sentencias de control ???

[[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/ejemplo%20bucle%20arduino.json)

![ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/ejemplo%20bucle%20arduino.png)

Podemos usar la forma cíclica (y unas variables globales) en la que se ejecutan los programas en Arduino para hacer un bucle sin más estructuras de control que una simple variable global

### Sonido

En bitbloq existen 2 formas de generar sonidos

* Reproducir notas musicales: podemos escoger la nota que vamos a reproducir y su duración


* ¿¿¿¿¿ Seleccionar la frecuencia exacta que queremos reproducir y su duración ???

![imagen](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/sonido.png) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/sonido.json)

## ¿¿¿¿¿ Librerías ????

En el caso de Bitbloq, ahora mismo no se pueden usar librerías, de forma manual.

### Servo

![imagen](./ejemplosBitbloq/Servo.png) [[ejemplo]](./ejemplosBitbloq/Servo.xml)

Para usar la librería Servo con bitbloq podemos usar los bloques Servo. Existen 2 tipos de servos: los de rotación continua y los normales.


## Entradas y salidas digitales

Veamos como podemos usar las entradas y salidas digitales

[[video]](https://youtu.be/GmvUamkeG4Y) [[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/pines%20digitales.json)


![imagen](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/pines%20digitales.png)

Veamos ahora como activar un led al pulsar un botón. Para ello añadiremos un botón y un led en el apartado del hardware

[[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/entradaysalidadigital.json)

![ejemplo](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/entradaysalidadigital.png)

## Entradas analógicas

[[video]](https://youtu.be/nChCA1Qc0uo)[[ejemplo]](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/entrada%20analogica.json)

![entradasanalogicas](https://raw.githubusercontent.com/javacasm/ArduinoBasico/master/bitbloq/entrada%20analogica.png)

Veamos como leer las entradas digitales



## ¿¿¿¿ Salidas analógicas (PWM) ????


![imagen](./ejemplosBitbloq/Salida_Analogica.png) [[ejemplo]](./ejemplosBitbloq/Salida_Analogica.xml)


Puedes encontrar más tutoriales en la página [oficial de bitbloq](http://diwo.bq.com/tag/bitbloq-2/)
