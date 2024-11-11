# Práctica 3 de Administración de Sistemas Unix/Linux

## Asegurar Bootloader

Primero accedemos al menú de edición de las entradas del GRUB y modificamos el inicio:

![Imagen 1](imgs/3.1.png)

Luego obtenemos la shell de root

![Imagen 2](imgs/3.2.png)
![Imagen 3](imgs/3.3.png)
![Imagen 4](imgs/3.4.png)

Cambiamos la contraseña:

![Imagen 5](imgs/3.5.png)

Y modificamos el archivo /etc/grub.d/10_linux:
![Imagen 7](imgs/3.7.png)

![Imagen 8](imgs/3.8.png)

Y usamos update-grub:

![Imagen 9](imgs/3.9.png)

Generamos nuestra contraseña. Esto lo hice desde otra máquina con SSH para poder copiar y pegar.

![Imagen 10](imgs/3.10.png)

La ponemos en el archivo /etc/grub.d/40_custom:

![Imagen 11](imgs/3.11.png)

![Imagen 12](imgs/3.12.png)

Y al modificar las entradas del GRUB nos pedirá contraseña: 

![Imagen 13](imgs/3.13.png)
