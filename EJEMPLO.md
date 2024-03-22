# Guía de Conexión SSH desde Windows a Kali Linux 👨‍💻
Esta guía proporciona instrucciones paso a paso sobre cómo establecer una conexión SSH desde un sistema Windows a una máquina que ejecuta Kali Linux.

## Requisitos previos
Asegúrate de tener instalado el servicio SSH en la máquina Kali Linux. Si no está instalado, puedes hacerlo utilizando el siguiente comando:
- sudo apt install openssh-server

## Iniciar el servicio SSH
Una vez instalado, inicia el servicio SSH en Kali Linux con el siguiente comando:
- sudo service ssh start

## Obtener la dirección IP y el puerto
Utiliza el comando ifconfig o ip a en Kali Linux para obtener la dirección IP y el puerto en el que está escuchando el servicio SSH.

## Establecer la conexión desde PuTTY
Abre PuTTY en tu sistema Windows.
En la interfaz de PuTTY, ingresa la dirección IP de Kali Linux en el campo "Host Name (or IP address)".
Asegúrate de que el puerto utilizado sea el mismo que el configurado en el servicio SSH de Kali Linux. Haz clic en "Open" para iniciar la conexión.

## Verificación
Una vez conectado, verifica que la conexión funciona correctamente.
Puedes realizar pruebas, como crear una carpeta o ejecutar comandos en la máquina de Kali Linux desde PuTTY.

![Connection](/Images/img-8.png)

¡Listo! Ahora has establecido una conexión SSH exitosa desde Windows a Kali Linux.

Esta guía proporciona los pasos esenciales para establecer la conexión SSH y puede ser ampliada según sea necesario, incluyendo más detalles sobre configuraciones específicas o solución de problemas comunes.