Son ternas de información que permiten el diálogo cliente-servidor sin que los datos se entreveren, están compuestos por un [[puerto]], un [[protocolo de transporte]] y una [[dirección IP]].

>[!info] Uno podría preguntarse: ¿cómo pueden entreverarse los datos?
>El profe propuso el siguiente ejemplo: una pantalla en la que quiero mostrar dos ventanas distintas, pero le pido al mismo servidor los datos.
>
>Entonces las máquinas tienen que ser capaces de mostrar lo que se pide para cada ventana en su lugar correspondiente sin mezclar los datos. Esto puede ser posible mediante los sockets.

Existe un socket con los datos del cliente y otro con los datos del servidor. La petición y la respouesta se muestra en ambos sockets.