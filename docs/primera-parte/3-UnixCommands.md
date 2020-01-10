# Comandos Unix

``` bash
readlist /bin/bash
```

``` bash
echo $SHELL
```

``` bash
echo  $BASH_VERSION
```
## Informacion del Sistema Operativo

``` bash
uname
```

``` bash
uname -r
```

``` bash
uname -a
```
## Imprimiendo mensajes en consola
``` bash
echo
```

``` bash
echo Linux Corazon
```

``` bash
echo El costo es $2.00
```
### Los metacharecters 
? [ ] ' " \ $ ; & ( ) | ^ < > *

``` bash
echo El costo es \$2.00
```

``` bash
echo Is Schrodinger\'s cat alive or dead\?
```

``` bash
echo Is "Schrodinger's" cat alive or "dead?"
```

``` bash
echo "Is Schrodinger's cat alive or dead?"
```

``` bash
echo 'Is Schrodinger's cat alive or dead?'
```
## Navegacion entre la estructura del directorio

### Conociendo el entorno de trabajo
``` bash
pwd
```

### Cambiando de directorio

``` bash
cd 
```

``` bash
cd Documents/
```

``` bash
cd /etc
```
### Ruta o Dirección Absoluta
``` bash
/home/username/Escritorio/Archivos/
```

### Ruta o Dirección Relativa
``` bash
Escritorio/Archivos/
```

## Variables de Entorno y su configuración

``` bash
set
```
### Lista de Variables comunes
 * BASH_VERSION
 * EDITOR
 * GROUPS
 * HISTFILE
 * HISTSIZE
 * HOME
 * HOSTNAME
 * LANG
 * LC_*
 * LC_ALL
 * LD_LIBRARY
 * PATH3
 * PS1
 * PS2
 * PWD
 * SHLVL
 * TZ
 * UID
 * VISUAL
 
``` bash
echo $PATH
```

## Obteniendo ayuda por consola

``` bash
apropos <command name>
```

### Uso de opciones 

```bash 
ls -l
```

``` bash
ls -l -t
```

``` bash
commandname -<<x><y><z>...>
```

``` bash
ls -lt
```

``` bash
ls --all
```

``` bash
ls -a
```

``` bash
ls --author
```

``` bash
ls --block-size=<SIZE>
```


### Obteniendo información de Comandos
``` bash
man 
```

``` bash
man <command name>
```

``` bash
history
```

``` bash
apropos <command name>
```

## Uso de expresiones regulares

* 
``` bash
apropos <command name>
```

## Transferencia, redirección, y Canalizado o Tubería(Pipe)
``` bash
apropos <command name>
```

## Procesando de archivos texto
``` bash
cat -n<number lines> <filename>
```

``` bash
cut
```

``` bash
expand
```

``` bash
unexpand
```

``` bash
fmt
```

``` bash
pr
```

``` bash
head
```

``` bash
tail
```

``` bash
join
```

``` bash
paste
```

``` bash
sort
```

``` bash
uniq
```

``` bash
split
```

``` bash
od
```

``` bash
wc
```

``` bash
sed
```

!!! note "Considerar"
    Todos los comandos que se muestran en esta página no son todos los existentes, pero son esenciales de conocer.
    Además, en los siguientes capítulos se detallarán algunos otros.

