# Instalación-Slackware-Linux
### El primer paso es la configuración del sistema con la carateristicas solicitadas
**- 700MiB de memoria**

![Repositorio Github](Imagenes/Captura1.png)

**- 3.0 GB de almacenamiento**

![Repositorio Github](Imagenes/Captura2.png)

### El segundo paso es seleccionar la imagen ISO de slackware al DVD virtual

![Repositorio Github](Imagenes/Captura3.png)

**- Una vez iniciado se configuramos un idioma para el teclado, en mi caso el idioma español**

![Repositorio Github](Imagenes/Captura4.png)

**- Se inicia sesion como "root"**

![Repositorio Github](Imagenes/Captura5.png)

### Para empezar el proceso de particion se usa el comando "cfdisk**

![Repositorio Github](Imagenes/Captura6.png)

**- Lo que nos da acceso al siguiente menú, donde se selecciona la opcion "dos"**

![Repositorio Github](Imagenes/Captura7.png)

**- Le damos a agregar una nueva particion:**

![Repositorio Github](Imagenes/Captura8.png)

**- Elegimos su tamaño en mi caso "1.5G"**

![Repositorio Github](Imagenes/Captura9.png)

**- Se pone de tipo primario**

![Repositorio Github](Imagenes/Captura10.png)

**- Cambiamos su tipo a "Linux Swap"**

![Repositorio Github](Imagenes/Captura11.png)

**-Repetimos el proceso para una nueva particion pero de tipo "Linux"

![Repositorio Github](Imagenes/Captura12.png)

**-Elegimos "write" para escribir las dos particiones, y aceptamos esta accion con "yes"**

![Repositorio Github](Imagenes/Captura13.png)

**- Salimos del apartado**

![Repositorio Github](Imagenes/Captura14.png)

**- Verificamos que se hayan creado las particiones correctamente**

![Repositorio Github](Imagenes/Captura15.png)

**- Como la primera partiicon no fue detectada correctamente como "Swap", realizamos su activacion**

![Repositorio Github](Imagenes/Captura16.png)

**- Ahora continuamos iniciando el "setup"

![Repositorio Github](Imagenes/Captura17.png)

**- En este caso como ya tenemos definido nuestro "keymap" continuamos con "AddSwap", donde nos detecta la primera particion como una posible ubicaion del swap, a lo que aceptaremos**

![Repositorio Github](Imagenes/Captura18.png)

**- Una vez aceptado nos indica que el "sawp" ya fue configurado**

![Repositorio Github](Imagenes/Captura19.png)

**- Seleccionamos la particion donde queremos que se instale el sistema**

![Repositorio Github](Imagenes/Captura20.png)

**-En nuestro caos vamos a sellecionar el "Filesystem" ext4**

![Repositorio Github](Imagenes/Captura21.png)

**-Seleccionamos la primer opcion de la instalacion**

![Repositorio Github](Imagenes/Captura22.png)

**- Configuramos lo que queremos que se instale**

![Repositorio Github](Imagenes/Captura23.png)

**- Elegimos una instalacion guiada, para poder controlar el almacenamiento que vamos a usar**

![Repositorio Github](Imagenes/Captura24.png)



