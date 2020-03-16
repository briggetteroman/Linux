# Preparativos previos a la instalación
## Creación de USB Booteable
### Windows

### Linux

#### Interfaz gráfica (GUI)
En este caso usare la herramienta `Disks` que viene instalado por defecto en Ubuntu.
Como se observa en la imagen, basta con buscarlo directamente con el nombre `Disks` o `Discos`.

![Disks](disks.png)
 <!-- <img src="disks.png" >  -->
Una vez abierta la herramienta, se procederá a escoger el Dispositivo de Almacenamiento para crear el USB Booteable
!!! warning "Considerar"
    Que el Disco Duro también es un dispositivo de almacenamiento por lo tanto estará listado. Cuidado con escoger el disco duro para crear el Booteable.


#### Comando de Linea (CLI)
Como no siempre se tiene interfaz gráfica, aquí explicaré el uso del comando `DD` o Copia en Duro para la creación de un USB boot.


1. Debemos encontrar la ruta donde se encuentra montado nuestro USB para ello usaremos el comando `df`, que nos listará todas las particiones que tiene montado el sistema operativo.
``` bash
df -h
```


``` bashheight="42" width="42"
dd if= of= 
```

## Preparar una maquina Virtual
### VirtuaBox
#### Software a descargar

### VMWare
#### Software a descargar