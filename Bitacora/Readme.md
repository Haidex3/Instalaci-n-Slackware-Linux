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

**- La primer parte debemos instalarla obligatoriamente**

![Repositorio Github](Imagenes/Captura25.png)

**- Luego de configurar todo lo que queriamos instalado, con aparecesara la siguiente opcion, en nuestro caso le dare "skip"**

![Repositorio Github](Imagenes/Captura26.png)

**- Instalamos Lilo**

![Repositorio Github](Imagenes/Captura27.png)

**- Elegimos la forma estandar**

![Repositorio Github](Imagenes/Captura28.png)

**- En este punto no es necesario poner parametros**

![Repositorio Github](Imagenes/Captura29.png)

**- En este caso vamos a seleccionar el "mbr" como destino para la instalacion de LILO

![Repositorio Github](Imagenes/Captura30.png)

**- Elegimos que servicios queremos en el inicio**

![Repositorio Github](Imagenes/Captura31.png)

**- Configuraciones varias**

![Repositorio Github](Imagenes/Captura32.png)

![Repositorio Github](Imagenes/Captura33.png)

**- Configuramos una contraseña para el usuario**

![Repositorio Github](Imagenes/Captura34.png)

**- Y con esto terminamos la parte del "Setup", ahora reiniciamos**

![Repositorio Github](Imagenes/Captura35.png)

### El cuarto paso es configurar una tarjeta de red de la siguiente manera:

![Repositorio Github](Imagenes/Captura36.png)

**- Usando el comando "netconfing", empezamos la configuracion, el primer paso el darle un nombre cualquiera**

![Repositorio Github](Imagenes/Captura37.png)

**- Al dominio en este caso usamos:**

![Repositorio Github](Imagenes/Captura38.png)

**- Seleccionamos "static IP"**

![Repositorio Github](Imagenes/Captura39.png)

**- Ingresamos la ip, cambiando los dos ultimos digitos por el del pc a trabajar, en mi caso "34"**

![Repositorio Github](Imagenes/Captura40.png)

**- El siguiente número, solo cambiamos el ultimo por un numero entre 60 y 65**

![Repositorio Github](Imagenes/Captura41.png)

**- En "IPv4 Addresses cambiamos en 24 por 16**

![Repositorio Github](Imagenes/Captura42.png)

**- Hacemos un reboot**

![Repositorio Github](Imagenes/Captura43.png)

![Repositorio Github](Imagenes/Captura44.png)

**- Comprobamos la conexion a su mismo ping**

![Repositorio Github](Imagenes/Captura45.png)

**- Al intentar comprobar la conexion a google, notamos que fallo, por lo cual se tiene que arreglar nuevamente usando "netconfing", y cambiando donde anteriormente pusimos 60, por 61**

![Repositorio Github](Imagenes/Captura46.png)

**- Realizamos nuevamente la comprobacion:**

![Repositorio Github](Imagenes/Captura47.png)

**- Y finalmente comprobamos las conexiones que se nos piden**

![Repositorio Github](Imagenes/Captura48.png)

**- Para que se guarden los cambios a pesar de reiniciar la maquina entramos a la configuracion de la mascara y agregamos "NETMASK"**

![Repositorio Github](Imagenes/Captura49.png)
