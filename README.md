# Instalacion Jdk en ubuntu

## Introducción

En esta práctica instalaremos Java Jdk en ubuntu 20.04.


## Desarrollo de la practica con Java

Lo primero que haremos será crear una máquina virtual con el SO Ubuntu. Para ello utilizaremos virtual box. Empezaremos a poner las diferentes características de la maquina como su RAM y su espacio en el disco. En mi caso he puesto 2048mb de RAM y 10Gb de espacio.

Una vez creada nos tocara montar la imagen del sistema operativo a la máquina virtual. Después iniciaremos la máquina y procederemos a configurar el SO.

El siguiente será actualizar el sistema, por lo tanto, le daremos a inicio y escribiremos "terminal". En el pondremos el siguiente comando "sudo apt-get update" y nos pedirá la contraseña del usuario para continuar. 

Una vez actualizado el sistema ingresaremos el siguiente comando para proceder a instalar JAVA, "sudo apt-get install default-jdk", una vez puesto el comando nos pedirá confirmación, ponemos S (si) y procederá a instalarse.

Lo siguiente que haremos es comprobar que versión estamos utilizando con el comando "Java –version", y en mi caso tenemos la versión 11, por lo tanto, tendremos que instalar la version 8 que es la que queremos utilizar, pondremos el comando "sudo apt install openjdk-8-jdk".

A continuacion procederemos a cambiar la version con el siguiente comando "sudo update- alternatives – config java" y seleccionaremos la versión 8.

## Imagenes de la práctica

<img src="instalacion de java en ubuntu/uno.png">

<img src="instalacion de java en ubuntu/dos.png">

<img src="instalacion de java en ubuntu/tres.png">

<img src="instalacion de java en ubuntu/cuatro.png>
          
