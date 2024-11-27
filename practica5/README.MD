# Práctica 5 de Administración de Sistemas Unix/Linux

## Compilar un Kernel 

Primero instalamos los paquetes necesarios:

![Imagen 1](imgs/5.1.png)

Luego descargamos el código fuente del kernel, en este caso estamos usando la versión 6.11.3: 

![Imagen 2](imgs/5.2.png)

Lo extraemos: 

![Imagen 3](imgs/5.3.png)

Luego copiamos nuestra configuración a un archivo .config:

![Imagen 4](imgs/5.4.png)

Y ejecutamos el siguiente comando para iniciar la configuración del nuevo kernel: 

![Imagen 5](imgs/5.5.png)

Abrirá una interfaz como la siguiente: 

![Imagen 6](imgs/5.6.png)

Utilizamos el archivo que acabamos de crear:

![Imagen 7](imgs/5.7.png)


![Imagen 8](imgs/5.8.png)


![Imagen 9](imgs/5.9.png)

Ejecutamos el comando
 ```
make -j $(nproc)
``` 
y esperamos a que termine: 

![Imagen 10](imgs/5.10.png)

Lo siguiente es ejecutar este comando para instalar los móodulos necesarios:

![Imagen 11](imgs/5.11.png)

Ahora sigue instalar el kernel: 

![Imagen 12](imgs/5.12.png)

Actualizamos el grub:

![Imagen 13](imgs/5.13.png)

Y verificamos que efectivamente se haya actualizado el kernel:

![Imagen 14](imgs/5.14.png)
