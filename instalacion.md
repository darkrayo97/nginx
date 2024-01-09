en primer lugar actualizamos un apt update por si acaso y en caso de actualizaciones apt upgrade

empezamos instalando

![cap2](instalacion.png)

segundo inicializamos nginx


![cap3](start.png)

comprobamos el servicio

![cap4](estado.png)

vamos a permitir http nginx con este comando

![cap5](permitirufw.png)

luego vamos a comprobar la lista de perfiles con este comando

![cap6](ufwlist.png)

si como yo en debian no os aparece el comando ufw tendreis que instalarlo de esta manera

![cap6](install.ufw.png)
