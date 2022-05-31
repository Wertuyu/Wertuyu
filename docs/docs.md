# Icinga
<font size=5>Instalación</font>

<font size=3>Primero debemos de instalar un servidor Lamp

![1](./imagenes/2.png)

Una vez instalado el servidor lamp procederemos con la instalación de Icinga con el siguiene comando

![1](./imagenes/3.png)

Marcamos la opción "Si"

![1](./imagenes/4.png)

Ahora proporcionamos la contraseña de de nuestro servidor de Icinga

![1](./imagenes/5.png)

Marcamos la opción "Si" 

![1](./imagenes/6.png)

Ahora debemos de habilitar funciónes de icinga2 mysql usando los siguientes comandos

![1](./imagenes/7.png)

Con el siguiente comando comprobaremos estado de icinga

![1](./imagenes/8.png)

Ahora procederemos a instalar IcingaWeb con el siguiente comando

![1](./imagenes/9.png)

Una vez descargado editaremos el fichero php de apache y cambiaremos la opcion date.time zone y añadiremos "Europe/London" y quitaremos el ; del parametro

![1](./imagenes/10.png)

Reiniciaremos apache


![1](./imagenes/11.png)

Con el siguiente comando generaremos el token de nuestro servidor el cual deberemos de guardar para usar mas adelante

![1](./imagenes/12.png)

Ahora desde un navegador accederemos con nuestra ip o con localhost en la siguiente ruta y nos pedira el token que acabamos de crear

![1](./imagenes/13.png)

Seleccionamos la opcion de "Monitoring" y marcamos next

![1](./imagenes/14.png)

Comprobaremos que los requisitos esten correctos y pulsamos next

![1](./imagenes/15.png)
![1](./imagenes/16.png)

En el desplegable debera de aparecer Database

![1](./imagenes/17.png)

Ahora crearemos el usuario de la base de datos admin


![1](./imagenes/18.png)

Para crear la base de datos nos pedira nuestro usuario root de nuestra maquina

![1](./imagenes/19.png)

Ahora escribiremos el nombre de nuestro servidor

![1](./imagenes/20.png)

Volveremos a escribir nuestro usuario de la base de datos admin

![1](./imagenes/21.png)

Escribiremos de nuevo el nombre de nuestro servidor y marcamos next

![1](./imagenes/22.png)

Pulsamos next en las siguientes capturas

![1](./imagenes/23.png)

![1](./imagenes/24.png)



![1](./imagenes/25.png)

Ahora escribimos el nombre de nuestra base de datos y añadiremos nuestro usuario root

![1](./imagenes/26.png)

Y volveremos a pulsar next hasta que se termine la instalación

![1](./imagenes/27.png)


![1](./imagenes/28.png)


![1](./imagenes/29.png)

Y habremos instalado el servidor web de Icinga
![1](./imagenes/30.png)

Iniciamos sesion con el usuario admin

![1](./imagenes/31.png)

Y habremos entrado en Icinga

![1](./imagenes/32.png)

Para monitorizar el otro equipo debermos acceder al siguiente archivo y añadir su ip


![1](./imagenes/33.png)

Despues de añadir su ip accederemos alsiguiente fichero y añadiremoslos servicios que queremos monitorizar

![1](./imagenes/34.png)

Reiniciamos el servicio de icinga

![1](./imagenes/35.png)

Y se visualizara la maquina que hemos añadido

![1](./imagenes/36.png)


</font>

Enlace a [Documentacion](..)