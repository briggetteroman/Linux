# Preparativos previos a la instalación
## Creación de USB Booteable
### Windows

### Linux

#### Interfaz gráfica (GUI)
En este caso usare la herramienta `Disks` que viene instalado por defecto en Ubuntu.
Como se observa en la imagen, basta con buscarlo directamente con el nombre `Disks` o `Discos`.

![](disks.png "disks")

Una vez abierta la herramienta.

!!! warning "Considerar"
    Que el `Disco Duro(HDD)` también es una unidad de almacenamiento por lo tanto estará listado. Cuidado con escoger el disco duro para crear el Booteable.

1. Se procederá a escoger la unidad de Almacenamiento para crear el USB Booteable.
![](selectDevice.png "device")


2. Luego en el menú ubicado en el lado derecho superior, como se observa en la imagen siguiente, y se le dará a la opción `Restore Disk Image`.
![](restoreDisk.png "restore image")

3. Aparecerá una ventana `Restore Disk Image`, que nos permitirá escoger la imagen `iso` que necesitamos al dar clic en `Image to Restore` para el Booteable. 
![](restoreImageWindow.png "restore image window")

4. Después de seleccionar la imagen `iso` puede aparecer una alerta. Esto se debe a que el tamaño de la imagen `iso` es muy pequeña comparado con la capacidad de almacenamiento del USB, es decir te sobra espacio de almacenamiento en el USB. Por lo que se puede continuar con el proceso dandole clic en `Start Restoring...`.
![](selectIso.png "select Image")

5. Antes de comenzar la restauración, te aparecerá una ventana para corroborar la unidad escogida. Dar clic en `Restore` para comenzar el proceso.
![](confirmDevice.png "confirm Device")

6. Comenzará el proceso de generar un USB Booteable.
![](processRestore.png "process Restore")

#### Comando de Linea (CLI)
Como no siempre se tiene interfaz gráfica, aquí explicaré el uso del comando `DD` o Copia en Duro para la creación de un USB boot.


1. Debemos encontrar la ruta donde se encuentra montado nuestro USB para ello usaremos el comando `df`, que nos listará todas las particiones que tiene montado el sistema operativo.
``` bash
df -h
```

``` bash
dd if= of= 
```

## Preparar una maquina Virtual
### VirtuaBox
#### Software a descargar

### VMWare
#### Software a descargar