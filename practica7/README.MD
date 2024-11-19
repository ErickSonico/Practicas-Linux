# Práctica 7 de Administración de Sistemas Unix/Linux

## Fail2ban, ClamaV, Postfix y Logwatch

### Fail2ban
Iniciamos con el respectivo update:

![Imagen 1](imgs/7.1.png)

Instalamos fail2ban: 

![Imagen 2](imgs/7.2.png)

Nos dirigimos al directorio donde está el archivo de configuración y creamos una copia del mismo para hacer modificaciones:

![Imagen 3](imgs/7.3.png)

Las modificaciones:

![Imagen 4](imgs/7.4.png)

Verificamos el estado del serivicio y lo habilitamos: 

![Imagen 5](imgs/7.5.png)

Luego revisamos el estatus de sshd

![Imagen 6](imgs/7.6.png)

---

### ClamaV

Lo primero es instalarlo:

![Imagen 7](imgs/7.7.png)

Al instalarlo aparecerá la interfaz para configurarlo:

![Imagen 8](imgs/7.8.png)

![Imagen 9](imgs/7.9.png)

![Imagen 10](imgs/7.10.png)

Revisamos el servicio:

![Imagen 11](imgs/7.11.png)

Y modificamos el archivo de las tareas diarias:

![Imagen 12](imgs/7.12.png)

Y realizamos un escaneo manual: 

![Imagen 14](imgs/7.14.png)

---

### Postfix y Logwatch

Nuevamente los instalamos primero:

![Imagen 15](imgs/7.15.png)

Y procedemos con la configuración:

![Imagen 16](imgs/7.16.png)

![Imagen 17](imgs/7.17.png)

Definimos el correo al que llegarán los mails con los logs: 

![Imagen 18](imgs/7.18.png)

Aquí se configura la forma en que se mostrará la salida, en este caso es por correo:

![Imagen 19](imgs/7.19.png)

Se tuvieron que realizar los siguientes comandos:

![Imagen 20](imgs/7.20.png)

Revisamos el buzón de root, que es donde está el informe que se generó con el comando anterior:

![Imagen 21](imgs/7.21.png)

