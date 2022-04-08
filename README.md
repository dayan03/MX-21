# MX-21
instalacion de sistema operativo MX-21

integrantes:
Juan Felipe Merchancano
Diana Leonela Atehortua Caicedo
Duvan Aguirre

hecho para el Docente :
Giancarlos Benavides

Paso 1:
Al momento de instalar MX-21 lo primero se debe instalar la imagen iso  de MX Linux.

Luego de que se haya descargado,se debe asegurar que la bios este configurada.


PASO 2: instalación de Mx-linux
Al momento de arrancar el sistema, hay que seleccionar la primera que tiene el nombre de la maquina MX-21 x64,luego damos click en la opción que dice instalar MX-linux

PASO 3: configuración de teclado
Se debe seleccionar opción de teclado apropiado deacuerdo a la preferencia del usuario

PASO 4: Particion del disco
Para la partición hay formas de instalar.se puede instalar atraves de modo habitual o automáticamente, o se puede  personalizar manualmente las particiones de este, pudiendo le dar el tamaño correspondiente a las preferencias del usuario para cada, directorio que manejara la maquina virtual

![imagen 1](img/ima1.jpg)

Además emerge una sale una alerta en la que pregunta si se quiere guardar los cambios.

![imagen 2](img/ima2.jpg)


A continuación se descargaran todos los paquete indispensables  para  la instalación y funcionamiento .
La barra indica el progreso de la instalación de la información requerida
![imagen 3](img/ima3.jpg)

PASO 5:
Configurar el nombre de la computadora  y si es necesario el dominio.
![imagen 4](img/ima4.jpg)


PASO 6:
Se debe configurar una cuenta raíz y una cuenta normal  especificándole el nombre de usuario y contraseña segura.
Darle click en siguiente 
![imagen 5](img/ima5.jpg)


Por lo tanto,seguirá  con la instalación para descargar los paquetes faltantes,además de el arranque del GRUB,de tal manera  que se instale todo lo necesario y  no produzca ningún error

PASO  7: termina instalación y se reinicia
Al momento de terminar la instalación y antes de reiniciar ,saldrá una ventana emergente que pedirá  que elimine el medio de instalación o remover el disco,  de manera que se le deberá dar ENTER,para que reinicie la instalación de la MX-21

![imagen 6](img/ima6.jpg)

![imagen 7](img/ima7.jpg)


PASO 8:
Aquí se completa instalación del sistema de la maquina virtual MX-21
![imagen 8](img/ima8.jpg)


![imagen 9](img/ima9.jpg)



2)	 MX Linux es un sistema operativo Linux ligero basado en Debian estable, con los componentes centrales de antiX, con software adicional creado y empaquetado por MX Community. Se desarrolla como una empresa cooperativa entre las comunidades de antiX y el antiguo MEPIS, con el objetivo de utilizar las mejores herramientas y talentos de cada una de estas distribuciones.

<b>VENTAJAS </b>

•	Varias aplicaciones nuevas y actualizadas.

•	Una nueva área de selección de particiones del instalador: Lo cual incluye algo de soporte para lvm si el volumen lvm ya existe.

•	Nuevos menús de arranque del sistema en vivo UEFI: Los cuales permiten seleccionar las diversas opciones de arranque en vivo (persistencia, entre otras) desde el menú de arranque y los submenús en lugar de utilizar los menús de consola anteriores.

•	Los Entornos de Escritorio XFCE 4.16 y Plasma 5.20, más el gestor de Ventanas Fluxbox 1.3.7 con configuraciones en mx-fluxbox 3.0.

•	Contraseña de usuario (sudo) para las tareas de administración por defecto: Lo cual puede ser cambiado en la opción de configuración siguiente: MX-Tweak + Otras pestañas.

3)
“XFCE es un entorno de escritorio ligero para sistemas tipo UNIX. Su objetivo es ser rápido y usar pocos recursos del sistema, sin dejar de ser visualmente atractivo y fácil de usar”.
“XFCE 4.16 encarna la filosofía tradicional UNIX de modularidad y reutilización. Se compone de una serie de aplicaciones que proporcionan toda la funcionalidad que se puede esperar de un moderno entorno de escritorio. Se empaquetan por separado y puede escogerse entre los paquetes disponibles para crear un entorno óptimo personal para el trabajo

<B>VENTAJAS ENTORNO ESCRITORIO</B>

•	Una sólida trayectoria histórica.
•	Ofrece un excelente equilibrio entre velocidad, estabilidad y configuración.
•	Muy usado como Entorno de Escritorio por defecto en muchas Distros.
•	Muy personalizable y ligero, sobre todo a nivel del Panel y el Escritorio mediante ajustes y widgets (goodies).
•	Compatibilidad nativa con aplicaciones de GNOME debido a que ambos usan GTK+. Aunque puede ejecutar muy bien aplicaciones de KDE Plasma si el mismo se encuentra instalado de forma mínima con sus librerías necesarias, sobre el Sistema Operativo.
4)

Thunar, con funciones básicas para ordenadores poco potentes

Pasamos ahora a un explorador de archivos que encontramos en las distribuciones con entorno gráfico XFCE, siendo un administrador con funciones básicas para optimizar al máximo los recursos del sistema. Es sencillo de usar y cuenta con funciones como arrastrar y soltar, tres tipos de vistas de carpetas (iconos, lista compacta y lista detallada) y acceso a carpetas en remoto (NFS, samba, FTP, cámaras, etc).

Se puede personalizar de muchas maneras para ajustarlo a nuestros gustos, siendo muy eficiente tanto para iniciar archivos en programas externos como para mover y copiar archivos. Quizás no tenga la popularidad y la potencia de otros gestores, pero puede ser ideal para equipos antiguos o poco potentes que solo necesitan de un administrador de archivos básico. En su contra, decir que no incluye un buscador integrado en su interfaz, algo que se puede solucionar instalando catfish como complemento.

<b>VENTAJAS DE EXPLORADOR DE ARCHIVOS</b>


Thunar es un gestor teóricamente ligero -bastante más que Nautilus o Konqueror/Dolphin- y que puede ser un componente curioso para sustituir a esas aplicaciones.
Es lo que indican en TuxArena, donde hablan de este explorador que quizás no tenga tantas características como Nautilus o Dolphin, pero a los que barre en el terreno de la velocidad. Me parece una apuesta interesante para aquellos con máquinas con recursos más limitados 

 la interfaz y forma de funcionamiento de Thunar es atractiva, y por ejemplo dispone de los emblemas para calificar rápidamente a ficheros y carpetas y asignarles ciertos permisos de forma automatizada.
 Entre las ventajas de Thunar está la facilidad a la hora de crear diversas acciones predeterminadas para, por ejemplo, extraer ficheros de un archivo comprimido.
La verdad es que es un buen explorador, y podéis usarlo aunque no estéis usando XFCE como entorno de escritorio, así que igual os apetece echarle un vistazo.

5)

deb es la extensión del formato de paquetes de software de la distribución de Linux, Debian GNU/Linux y derivadas, y, el nombre más usado para dichos paquetes. Como Debian, su nombre proviene de Deborah Murdock, exesposa del fundador de la distribución Ian Murdock.
Synaptic es un programa informático que consiste en la interfaz gráfica GTK+ de APT, para el sistema de gestión de paquetes de Debian GNU/Linux. Generalmente se utiliza Synaptic para sistemas basados en paquetes .deb pero también puede ser usado en sistemas basados en paquetes RPM.

<b>VENTAJAS DE SISTEMA DE GESTION DE PAQUETES</b>
El Administrador de paquetes Synaptic tiene muchos beneficios al compararlo con el Centro de software de Ubuntu, uno de ellos es el hecho de que no hay anuncios de software pagos y el otro es que siempre verás los resultados de todos los repositorios dentro de tu lista sources.list.
Otro beneficio de Synaptic es que se trata de una aplicación que se utiliza en muchas otras distribuciones de Linux basadas en Debian. Si te acostumbras al uso de Ubuntu, y luego decides cambiarlo por otra distribución, tendrás una aplicación con la que ya estés familiarizado, lo que te ayudará con la instalación de otras aplicaciones.

6)
La serie MX-14 se basó en Debian Estable "Wheezy" y usó primero XFCE 4.10 y luego, con la versión 14.4, XFCE 4.12. Las versiones MX-14 fueron pensadas para caber en un CD, una restricción que limita las aplicaciones que podrían incluirse. Esta serie vio la evolución gradual de las herramientas MX, una colección de utilidades prácticas diseñadas para ayudar al usuario con una variedad de tareas comunes que a menudo son complicadas.
MX-15 se mudó al nuevo Debian Estable "Jessie" usando systemd-shim, lo que significa que systemd está instalado pero el inicio predeterminado es sysvinit.3 Se eliminó la limitación de tamaño, lo que permitió a los desarrolladores presentar al usuario un producto completo. Expansión sustancial de las herramientas MX.
MX-16 todavía estaba basado en Debian Estable "Jessie" pero con muchas aplicaciones respaldadas y agregadas también de otras fuentes. También tenía adiciones y mejoras a las herramientas MX, importación de desarrollos avanzados antiX, soporte expandido y una combinación completamente nueva de íconos / temas / fondos de pantalla.
MX-16.1 recopiló todas las correcciones de errores y mejoras desde MX-16 y agregó un nuevo tema de Kingfisher, herramientas MX mejoradas y optimizadas, documentación revisada y nuevas traducciones.
MX-17 cambia su base a Debian 9 (Stretch), y trae ilustraciones mejoradas, nuevas herramientas MX, funcionamiento en vivo mejorado a través de antiX y muchos otros cambios detallados en el Blog de MX.
MX-18 continúa con el desarrollo de las herramientas MX, presenta un núcleo muy reciente, permite el cifrado de todo el disco y agrega temas de grub y funcionalidad de bienvenida a través de las opciones de arranque MX. Se han incluido nuevas ilustraciones y una mejor localización. Detalles en el Blog de MX.
MX Linux 19 «Patito Feo» en la nueva versión de la distribución, como novedad principal se destaca que la base del sistema se ha actualizado a Debian 10 “Buster” junto con algunos paquetes de los últimos repositorios antiX y MX
MX-21 “Wildflower” se lanzó el 21 de octubre del 2021, teniendo como novedad tener su base en Debian 11 (Bullseye) 

