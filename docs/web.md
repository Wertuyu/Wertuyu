# Icinga
<font size=5>Monitorización</font>

<font size=3>

Para monitorizar una Web deberemos añadir la ip y la direccion de la pagina que vamos a monitorizar en el fichero /hosts.conf de la siguiente forma. 

![1](./imagenes/57.png)

Ahora deberemos de añadir en el archivo /services.conf el servicio que monitorizara el estado de la web.

Escribiremos solamente la opcion certificado:

![1](./imagenes/58.png)

Reiniciamos el servicio de icinga

![1](./imagenes/52.png)

Y se deberia de visualizarse el estado de la web.

![1](./imagenes/59.png)

Para comprobar que funciona he hecho lo mismo pero con la pagina de google.es

![1](./imagenes/60.png)

</font>