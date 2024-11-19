# Práctica 6 de Administración de Sistemas Unix/Linux

## phpMyAdmin

Después de instalar apache2 y mariadb-server continuamos con la configuración de seguridad del server de mariadb:

![Imagen 1](imgs/1.png)

![Imagen 2](imgs/2.png)

Ya podemos ejecutar comandos:

![Imagen 3](imgs/3.png)

Luego se instalan los demás paquetes necesarios: 

![Imagen 4](imgs/4.png)

Y se modifica el dir.conf para servir archivos .php:

![Imagen 5](imgs/5.png)

Más paquetes:

![Imagen 6](imgs/6.png)

Descargamos el código fuente de phpMyAdmin: 

![Imagen 7](imgs/7.png)


Y movemos la carpeta extraída a la ubicación necesaria, además de crear directorios y modifcar los permisos; 


![Imagen 10](imgs/10.png)

Ahora instalamos pwgen para generar nuestra cadena segura: 

![Imagen 11](imgs/11.png)

Realizamos las modificaciones necesarias en config.inc.php:

![Imagen 12](imgs/12.png)

![Imagen 13](imgs/13.png)

![Imagen 14](imgs/14.png)

![Imagen 15](imgs/15.png)

Y creamos el esquema de la BD:

![Imagen 16](imgs/16.png)

También creamos nuestro usuario y el usuario pma:

![Imagen 22](imgs/22.png)

Copiamos el archivo de configuración por defecto para phpMyAdmin: 

![Imagen 19](imgs/19.png)

Habilitamos la configuración en apache2 y reiniciamos el servicio:

![Imagen 20](imgs/20.png)

Y accedemos a él con nuestro usuario y contraseña: 

![Imagen 21](imgs/21.png)

