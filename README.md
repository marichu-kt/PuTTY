# PuTTY 🚀

PuTTY es un cliente de terminal gratuito y de código abierto que soporta varios protocolos de red, incluyendo SSH, Telnet, SCP, y más. Es ampliamente utilizado en entornos de administración de sistemas y desarrollo de software para acceder y gestionar servidores remotos de forma segura a través de una interfaz de línea de comandos.

![PuTTY](/Images/icon.jpg)

## Características principales 🎯

- Soporte para múltiples protocolos de red, incluyendo SSH, Telnet, Rlogin, SCP, y Raw socket connection.
- Interfaz de usuario simple y fácil de usar.
- Compatible con una amplia gama de sistemas operativos, incluyendo Windows, macOS y Linux.
- Funcionalidad de emulación de terminal avanzada, que incluye soporte para varios tipos de terminal como xterm, VT100, VT102, entre otros.
- Opciones de configuración flexibles para adaptarse a las necesidades individuales del usuario.
- Integración con herramientas de cifrado como SSH para asegurar las comunicaciones.

## Instalación 🛠️

Para instalar PuTTY, sigue estos pasos:

1. Descarga el instalador adecuado para tu sistema operativo desde el sitio web oficial de PuTTY: [putty.org](https://www.putty.org/).
2. Ejecuta el instalador y sigue las instrucciones en pantalla.
3. Una vez completada la instalación, PuTTY estará listo para usar.

## Uso 🖥️

Para utilizar PuTTY, simplemente sigue estos pasos:

1. Abre PuTTY desde el menú de inicio o buscándolo en el sistema.
2. En la ventana de PuTTY, ingresa la dirección IP o el nombre de host del servidor al que deseas conectarte.
3. Selecciona el protocolo de red adecuado (por ejemplo, SSH para conexiones seguras).
4. Haz clic en "Abrir" para iniciar la conexión.
5. Ingresa tus credenciales de autenticación cuando se te solicite.
6. Una vez conectado, podrás interactuar con el servidor a través de la interfaz de línea de comandos de PuTTY.

#
#

# Personalización 🧢

## Loggin (Sesiones)
En el apartado de "Loggin" (Sesiones), activa la opción para registrar todas las sesiones en un archivo de registro. Además, configura el sistema para que siempre te pregunte si deseas guardar estas sesiones marcando las opciones indicadas en los recuadros en rojo.

![Loggin](/Images/img-1.png)

## Terminal - Bell
Dentro de "Terminal" en la sección "Bell", desactiva el sonido del Beep y cámbialo por una animación visual más agradable para las notificaciones.

![Terminal](/Images/img-2.png)

## Window - Scrollback
En el apartado de "Window", establece el valor de scrollback en 0 para tener un número ilimitado de líneas en la terminal y así evitar la pérdida de información.

![Window](/Images/img-3.png)

## Window - Colours
En la sección de "Window" - "Colours", personaliza los colores de la terminal para que se ajusten a tus preferencias o al esquema de colores del sistema.

![Window](/Images/img-4.png)

## Connection - Inactivity Timeout
En la configuración de "Connection", asegúrate de que la sesión no se corte por inactividad. Para ello, establece un valor positivo en segundos para que el sistema envíe señales "keep alive" periódicamente y así evitar el cierre automático de la sesión.

![Connection](/Images/img-5.png)

## Connection - Data
Dentro de "Connection" - "Data", puedes establecer un nombre de usuario predeterminado si inicias sesión repetidamente desde la misma máquina.

![Connection](/Images/img-6.png)

## Connection - Proxy
En el apartado de "Connection" - "Proxy", configura tus propios proxies para acceder a tu máquina de forma más segura. Por ejemplo, podrías utilizar Tor como proxy ingresando el host 127.0.0.1 y el puerto predeterminado 9050, preferiblemente utilizando el tipo SOKS5.

![Connection](/Images/img-7.png)

#
#

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

Esta guía proporciona los pasos esenciales para establecer la conexión SSH incluyendo detalles sobre configuraciones específicas.
