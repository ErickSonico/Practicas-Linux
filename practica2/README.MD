# Práctica 2 de Administración de Sistemas Unix/Linux
---
## Configuración con GParted

Primero descargamos el archivo de gparted:
![Imagen 1](imgs/2.1.png)

Y vertificamos la información de la máquina con los comandos:
![Imagen 2](imgs/2.2.png)

Y elegimos el archivo en los ajustes de la MV:
![Imagen 3](imgs/2.3.png)

Para poder arrancar con gparted, tuve que modificar opciones de la máquina para poder acceder boot menu, ya que no detectaba la iso. 
![Imagen 4](imgs/2.4.png)

Configuración de Gparted:
![Imagen 5](imgs/2.5.png)

![Imagen 6](imgs/2.6.png)

Realizamos las modificaciones a las particiones para mover el espacio no asignado:
![Imagen 7](imgs/2.7.png)

![Imagen 8](imgs/2.8.png)

![Imagen 9](imgs/2.9.png)

![Imagen 10](imgs/2.10.png)

![Imagen 11](imgs/2.11.png)

Terminamos con el espacio al lado de /dev/sda1
![Imagen 12](imgs/2.12.png)

Y aumentamos su espacio:
![Imagen 13](imgs/2.13.png)

Guardamos los cambios: 
![Imagen 14](imgs/2.14.png)

Quitamos la iso:
![Imagen 15](imgs/2.15.png)

Y verificamos en la máquina: 
![Imagen 16](imgs/2.16.png)

---

## Configuración con LVM

Podemos aumentar el espacio desde las configuraciones de la VM:
![Imagen 17](imgs/2.17.png)

Revisamos los discos en la vm, notemos que sda ocupa 30G:
![Imagen 18](imgs/2.18.png)


Instalamos las utilerías necesarias:
![Imagen 19](imgs/2.19.png)

![Imagen 20](imgs/2.20.png)

Y utilizamos los comandos:
![Imagen 21](imgs/2.21.png)

![Imagen 22](imgs/2.22.png)

![Imagen 23](imgs/2.23.png)

![Imagen 24](imgs/2.24.png)

![Imagen 25](imgs/2.25.png)

![Imagen 26](imgs/2.26.png)


