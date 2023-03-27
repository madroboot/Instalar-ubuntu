# Instalar-ubuntu

## Sobre Ubuntu, ¿Que es Ubuntu?

La distribución de Ubuntu representa lo mejor de lo que la comunidad mundial de software ha compartido con el mundo. Ubuntu es una distribución Linux basada en Debian GNU/Linux, que incluye principalmente software libre y de código abierto.

Puede utilizarse en ordenadores y servidores. Está orientado al usuario promedio, con un fuerte enfoque en la facilidad de uso y en mejorar la experiencia del usuario. Está compuesto de múltiple software normalmente distribuido bajo una licencia libre o de código abierto. Estadísticas web sugieren que la cuota de mercado de Ubuntu dentro de las distribuciones Linux es, aproximadamente, del 52 %,3​4​ y con una tendencia a aumentar como servidor web.

 [Referencia wikipedia] (https://es.wikipedia.org/wiki/Ubuntu) 
 
## Como puedo instalarlo?

### 1. Descargar VirtualBox

• Se puede descargar VirtualBox 
con el siguiente enlace:

https://www.virtualbox.org/wiki/Downloads

### 2. Instalar VirtualBox

• Una vez descargado, diríjete a la localización del paquete en tu
equipo (generalmente en el directorio “Descargas”) y ejecútalo
como administrador haciendo clic derecho.

• Comienza la instalación y espera hasta su finalización.

### 3. Descargar una Imagen ISO

Los archivos ISO proporcionan una imagen completa de un CD o DVD.
Montar una imagen ISO en VirtualBox ofrece la misma experiencia que
insertar un CD o DVD físico en cualquier computadora para instalar un
programa.

Por lo tanto, es necesario contar primero con la Imagen ISO del sistema
operativo que desea montar como máquina virtual en VirtualBox. Para
esto, utilizaremos el ISO :

[ubuntu-22.04.2-desktop-amd64.iso] (https://releases.ubuntu.com/jammy/)

Aunque tambien podemos usar cualquiera de lista de sistemas operativos libres,
pertenecientes a la familia de distribuciones Linux:

Ubuntu: https://ubuntu.com/

En esta ocasión, usaremos la imagen ISO de la distribución “Ubuntu”,
una de las más populares y de uso extendido. Puede ser descargada a
través de los recuros que encontramos en google.

### 4. Montar una máquina virtual Ubuntu

#### 1.)

Una vez instalado e iniciado VirtualBox, crearemos la máquina virtual pulsando el icono de «Nueva».

VirtualBox nos pedirá que introduzcamos el nombre de la máquina virtual junto con el tipo y la versión que vayamos a usar. En este caso el tipo será «Linux» y la versión será «Ubuntu (64-bit)». 

El nombre puedes introducir el que quieras. Este será el que te permita identificar la máquina virtual en caso de tener más de una. Además de esto, te permite introducir la carpeta donde alojar los archivos de la máquina virtual. 

![paso 1](ubuntu1png.png)

 #### 2.)

En el siguiente paso, debemos indicarle la memoria principal (RAM) que tendrá nuestra máquina virtual. En este caso Ubuntu recomienda escoger un tamaño mínimo de 2048MB (2GB) para sistemas virtualizados para que todo funcione correctamente.

![paso 1](ubuntu2.png)

#### 3.)

 En segundo lugar, VirtualBox nos pedirá como configurar el disco duro. En este caso crearemos un disco virtual. El resultado de este paso será creación de un archivo que simulará el disco duro de tu máquina virtual. Como podemos ver en la segunda imagen, nos preguntará que tipo de archivo de disco duro queremos usar. 

Todos los formatos presentados son válidos para nuestro uso. Básicamente las principales características de estos son que VDI es el formato predeterminado de VirtualBox.

![paso 1](ubuntu3.png)

En este punto ya tenemos creada nuestra máquina virtual con las opciones seleccionadas en los pasos anteriores. En la pantalla principal podemos ver como aparecen todas las características que hemos seleccionado en el proceso de creación de la máquina, aunque nos faltan algunas cosas por configurar. 

![paso 1](ubuntu4.png)

Los puntos que nos quedan por completar, se configurarán en el proceso de instalación del sistema operativo. La forma de iniciar este proceso será accediendo al menú «Configuración».

![paso 1](ubuntu5.png)

#### 4.)

Para poder usar una máquina virtual tienes que activar la virtualización en tu equipo. Normalmente esto ya viene activado por defecto, pero no siempre es el caso. Ahora crearemso la maquina virtual. 

![paso 1](ubuntu6.png)

### 5. Instalación del Ubuntu en el ordenador

#### 5.)

 El último paso para poder disfrutar de un sistema operativo Linux en nuestra máquina virtual es la instalación del sistema operativo. Para comenzar dicha instalación debemos seleccionar ,»Iniciar», teniendo marcada la máquina virtual configurada anteriormente.

![paso 1](ubuntu7.png)

#### 6.)

 Se abrirá una ventana de inicio del sistema operativo. Normalmente al principio hace un chequeo de errores en el disco. Simplemente tenemos que dejar que este termine.

Antes de iniciar la instalación, cabe destacar que puede que en algún momento no veamos el ratón fuera de la ventana de VirtualBox. Esto puede ocurrir debido a que el programa captura nuestro ratón como si perteneciese a la máquina virtual que estamos instalando. 

Para poder usar el ratón fuera de nuestra máquina virtual debemos pulsar la tecla «Control» de la derecha del teclado.

Cuando el chequeo termine, obtendremos la pantalla mostrada en la siguiente imagen. En ella nos pregunta si queremos probar o directamente instalar Ubuntu. Pulsaremos en probarlo y más adelante lo instalaremos. Cabe destacar que puedes elegir el idioma que prefieras seleccionándolo a la izquierda.

![paso 1](ubuntux.png)

#### 7.)

Se iniciará Ubuntu. Ahora mismo lo podríamos usar como si ya estuviese instalado, pero nada de esto se nos guardaría, por lo que vamos a proceder a instalarlo. Antes de esto, para hacer más cómoda la instalación, vamos a cambiar la resolución de la ventana para poder verla a un tamaño normal. 

Para esto pulsaremos en los tres iconos de arriba a la derecha y en el menú desplegable que aparece pulsaremos en «Configuración» .Una vez se abra la configuración, en el menú de la izquierda bajaremos hasta encontrar el apartado «Monitores». Pulsaremos y nos saldrán 4 opciones que modificar. En este caso nos centraremos en la resolución, la cual puedes cambiar a tu gusto.

Tras cambiar la resolución, si todo se ve correctamente, le indicamos que queremos «Mantener cambios» y cerramos la ventana de configuración.

![paso 1](5.png)

#### 8.)

Una vez de nuevo en el escritorio, veremos un icono llamado «Instalar Ubuntu 20.04.1 LTS». Pulsaremos sobre él para la iniciar la instalación. En el instalador como vemos en las siguientes imágenes, lo primero que nos pedirá será el idioma y la configuración del teclado. 

Normalmente, si estás conectado a internet ambos se detectarán automáticamente, pero si quieres otra configuración, podrás cambiarla sin ningún problema.

![paso 1](instalacion1.png)

![paso 1](instalacion2.png)

#### 9.) 

En el siguiente paso nos preguntará qué tipo de instalación queremos hacer. En este caso seleccionaremos la instalación normal, con actualizaciones de Ubuntu. Puede que al realizar este paso, la ventana se vuelva pequeña de nuevo. Si esto es así, sin cerrar la ventana de instalación, vuelve a realizar los pasos que se indicaron antes para cambiar la resolución.

Tras esto, el instalador nos pregunta dónde queremos instalar Ubuntu. Aquí seleccionaremos que queremos «Borrar el disco e instalar Ubuntu». Cabe destacar que esto no borrará nada del disco de tu ordenador personal, si no que borrará el disco virtual que creamos previamente en VirtualBox.

![paso 1](instalacion4.png)

![paso 1](instalacion5.png)

#### 10.) 

El instalador nos pedirá que indiquemos donde nos encontramos para ajustar nuestra zona horaria. Bastará con pulsar el país en el que te encuentres, para que este ajuste la zona horaria pertinente.

![paso 1](instalacion6.png)

#### 11.)  

Como siguiente y último paso antes del inicio de la instalación, Ubuntu nos solicitará el nombre del equipo, el nombre de usuario y la contraseña. Rellenaremos el formulario e indicaremos si queremos o no poner la contraseña al iniciar una sesión. Cabe destacar que debes poner una contraseña que posteriormente recuerdes, ya que esta se necesitará para instalar programas y administrar tu sistema operativo.

![paso 1](instalacion7.png)

#### 12.) 

Ya completado este paso, comenzará la instalación. Tendremos que esperar hasta que finalice y cuando esta termine reiniciar la máquina virtual. Al reiniciar la máquina virtual, antes de que se apague la máquina nos pedirá que extraigamos el medio de instalación y pulsemos «Enter». Como es una máquina virtual y no tenemos medio de instalación simplemente pulsaremos la tecla «Intro».

![paso 1](instalacionfinal.png)

##### Una vez llegado a este punto, ya tendrás la máquina virtual completamente funcional. 

## Actualización del sistema

Para actualizar el sistema de Ubuntu haremos uso de la maquina virtual "virtual box"

### Actualización desde linea de comandos

![1](https://user-images.githubusercontent.com/122264680/227876705-2ca63072-cc22-4bd0-a962-c8f7f726d2bc.png)
![2](https://user-images.githubusercontent.com/122264680/227876758-1424d7e4-d47e-4667-a07f-4c52ecd8a059.png)
![3](https://user-images.githubusercontent.com/122264680/227876754-0a926cdb-5c2d-4d21-b2f3-a64b7e7472a5.png)
![4](https://user-images.githubusercontent.com/122264680/227876749-8d1675e1-3762-4302-9d48-743e98105617.png)
![5](https://user-images.githubusercontent.com/122264680/227876927-bccffb4f-7fc0-46c2-86df-86a524422e02.png)
![6](https://user-images.githubusercontent.com/122264680/227876925-4cbf853f-a943-4f3d-ada7-895f8d7deea7.png)
![7](https://user-images.githubusercontent.com/122264680/227876923-7b16b0b5-7ce9-42e6-a67e-05c640283345.png)
![8](https://user-images.githubusercontent.com/122264680/227876917-51b056b1-ed4d-4758-b581-ec5d47b69695.png)
![9](https://user-images.githubusercontent.com/122264680/227876912-1ae54119-4dad-42bf-8f43-d82717018996.png)
![10](https://user-images.githubusercontent.com/122264680/227877044-1b5142d4-d76c-460c-857c-19a433b2b3e9.png)
![11](https://user-images.githubusercontent.com/122264680/227877042-7d47209d-ff6b-4ae7-a82b-d44f4a8a7ce3.png)
![12](https://user-images.githubusercontent.com/122264680/227877038-ca3fcd85-b306-40a5-ac2c-6988e927bb97.png)
![13](https://user-images.githubusercontent.com/122264680/227877037-dcf24118-b248-444c-8858-ce87624971f2.png)
![14](https://user-images.githubusercontent.com/122264680/227877033-8f40c159-abc0-4327-b4a0-c3866b87f8ab.png)
![15](https://user-images.githubusercontent.com/122264680/227877088-7b29e189-838e-49b2-8bb6-dc29b2988dc6.png)
![16](https://user-images.githubusercontent.com/122264680/227877085-6faf0c8d-d62f-41e0-8901-c8200e4245b7.png)
![17](https://user-images.githubusercontent.com/122264680/227877081-e3fa6c9e-783c-48d6-9b0c-38b85e298539.png)
![18](https://user-images.githubusercontent.com/122264680/227877076-c078de6d-9ff3-458c-88de-a7e5f98ce5ab.png)
![19](https://user-images.githubusercontent.com/122264680/227877071-de173bab-ad04-4d3a-b262-a98fcf37dab3.png)


### Actualización desde el interfaz gráfico

![1](https://user-images.githubusercontent.com/122264680/227880849-2f4fa240-508f-41d3-a97f-345888e71a4d.png)
![2](https://user-images.githubusercontent.com/122264680/227880856-68f76c16-b8d2-45a7-ba78-cf94bc6daaa6.png)
![3](https://user-images.githubusercontent.com/122264680/227880861-b35b740a-538a-4e98-8d00-1116604555eb.png)
![4](https://user-images.githubusercontent.com/122264680/227880862-9d0c75e6-0a62-483e-a3a9-fbbdf7869498.png)
![5](https://user-images.githubusercontent.com/122264680/227880864-f79bcfab-47df-4d15-a5cf-cb37a11c6db8.png)
![6](https://user-images.githubusercontent.com/122264680/227881028-555c8006-fdac-4c80-b4f4-91e1cd139d71.png)
![7](https://user-images.githubusercontent.com/122264680/227880931-ebeaf3b4-8671-4413-b56f-0733fad694e1.png)

### Actualización con synaptic

![1](https://user-images.githubusercontent.com/122264680/227889755-21300d4d-9583-4d02-89f7-cb1010bdf17b.png)
![2](https://user-images.githubusercontent.com/122264680/227889756-56ca079f-bd26-4fe7-88dd-897ac4d8a277.png)
![3](https://user-images.githubusercontent.com/122264680/227889759-e84a690b-1693-447b-944d-d4bddd159078.png)
![4](https://user-images.githubusercontent.com/122264680/227889762-34e7b275-8e9a-4a94-a051-d465cb26f21e.png)
![5](https://user-images.githubusercontent.com/122264680/227889766-d0fe62f3-4020-49e0-b241-a62b0b511671.png)
![6](https://user-images.githubusercontent.com/122264680/227889771-3add54f3-d079-4194-9432-d92ab0675f75.png)
![7](https://user-images.githubusercontent.com/122264680/227889774-f2b6fa93-6d86-4327-a9ed-2220a6567d29.png)
![8](https://user-images.githubusercontent.com/122264680/227889777-74b4570a-02af-4469-ad12-607e684d6d67.png)

#  Instalación de software

### Con ubuntu store

![1](https://user-images.githubusercontent.com/122264680/227887783-66f15df6-a727-401a-991d-bbf4a3198462.png)
![2](https://user-images.githubusercontent.com/122264680/227887786-12b54e78-87da-40e1-a67c-8b446d99407f.png)
![3](https://user-images.githubusercontent.com/122264680/227887789-fc112d85-34ec-481c-b6a2-323ee36c4b27.png)
![4](https://user-images.githubusercontent.com/122264680/227887795-a56d6771-f0bc-4092-a183-85b54fddd39e.png)
![5](https://user-images.githubusercontent.com/122264680/227887797-786c54c6-2e72-4d0e-b163-615c4e905373.png)
![6](https://user-images.githubusercontent.com/122264680/227887802-1ae2fff1-2d3d-4c24-aa34-9027d84fc230.png)

### Mediante SYNAPTIC 

![1](https://user-images.githubusercontent.com/122264680/227887706-14f0693f-ea6d-46b6-b3bf-453d24f659aa.png)
![2](https://user-images.githubusercontent.com/122264680/227887711-ad405dd7-590e-472e-98f7-49cfe65fe987.png)
![3](https://user-images.githubusercontent.com/122264680/227887714-bd111da7-38a5-4427-9bb1-841ab7db3912.png)
![4](https://user-images.githubusercontent.com/122264680/227887719-c4c58d2e-708a-4c51-bf64-0bd07bcc001c.png)
![5](https://user-images.githubusercontent.com/122264680/227887722-b6b071c0-5f74-4a0a-96b1-ca8eaecc78f6.png)
![6](https://user-images.githubusercontent.com/122264680/227887723-304eb05e-7174-4d70-b58b-bb1bae850fa7.png)
![7](https://user-images.githubusercontent.com/122264680/227887725-7f4acecb-2910-4c58-9efe-a2f4668c996f.png)
![8](https://user-images.githubusercontent.com/122264680/227887726-fd6e955b-73e0-4c73-81fc-dbe7dae86154.png)
![9](https://user-images.githubusercontent.com/122264680/227887727-26cdb3aa-a351-44e4-8756-6be4d9224cd9.png)
![10](https://user-images.githubusercontent.com/122264680/227887731-d19cbae2-0725-4eda-801f-156d85c0be8a.png)


### Con APT

![1](https://user-images.githubusercontent.com/122264680/227882471-94eb83ba-6b25-4a6c-9fb3-bc41405aceb9.png)
![2](https://user-images.githubusercontent.com/122264680/227882476-f7d37c4a-ab7d-439f-8f96-3a88911ba710.png)
![3](https://user-images.githubusercontent.com/122264680/227882479-b3bff2ca-30a5-41e4-8e63-5e2451f4eb08.png)
![4](https://user-images.githubusercontent.com/122264680/227882481-b3c80400-5092-440c-91cb-37a8eea02534.png)
![5](https://user-images.githubusercontent.com/122264680/227882483-e8c936d2-195c-43b0-8e8f-771c1a072499.png)
![6](https://user-images.githubusercontent.com/122264680/227882484-7be30386-a3b5-444d-922d-19814c67bc92.png)
