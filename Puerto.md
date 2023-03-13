Existe un puerto destinado al cliente y uno al servidor, por eso se explican en cuadros diferentes.

>[!important] Para el servidor
>El puerto es un número que identifica el servicio que será brindado, por ejemplo, el puerto 80 es utilizado para servicios web.

>[!important] Para el cliente
>Es un número que define el sistema operativo del cliente en cada momento, **no se puede conocer de antemano**.

Para entender mejor por qué existe el puerto de cliente, imaginemos que dos peticiones salen del mismo cliente al mismo servidor, lo único que le permite al servidor distinguir las peticiones entre sí es el puerto cliente. Por ende, aunque se genere en cada momento **es el mismo durante toda la conversación**.

