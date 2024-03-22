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

## Personalización 🧢

1. En el apartado de "Loggin" (Sesiones), si queremos que nos registre todas las sesiones en un log y que además 
   nos pregunte siempre si queremos que las guarde, deberemos marcar las opciones de los recuadros en rojo.
![Loggin](/Images/img-1.png)
2. En el apartado de "Terminal" - "Bell", podemos quitar el sonido del Beep y cambiarlo por una animacion visual.
![Terminal](/Images/img-2.png)
3. En el apartado de "Window", podemos poner el valor 0 en scrollback para tener lineas infinitas en la terminal para que no se pierdan.
![Window](/Images/img-3.png)
4. En el apartado de "Window" - "Colours", podemos personalizar los colores de la terminal como en el sistema o cualquiera que elijamos.
![Window](/Images/img-4.png)
5. En el apartado de "Connection", si queremos que no se corte la sesion por inactividad, debemos ponerle un valor positivo en segundos,
esto provocara que el sistema le mande señales "keep alive" cada cierto tiempo evitando que se cierre la sesion.
![Connection](/Images/img-5.png)
6. En el apartado de "Connection" - "Data", podemos poner un nombre de usuario predeterminado si vamos a iniciar sesion siempre con la misma maquina.
![Connection](/Images/img-6.png)
7. En el apartado de "Connection" - "Proxy", podemos configurar nuestros propios Proxies para acceder a nuestra maquina de una forma mas segura, 
   podriamos usar Tor como proxy, ingresando nuestro host 127.0.0.1 y el puerto predeterminado 9050, preferiblemente usar el tipo SOKS5.
![Connection](/Images/img-7.png)

## Ejemplo 👨‍💻


