# Instalación de Git en linux
Por Álvaro Fernández Martín

## Indice:
- Comprobamos los Requisitos previos
- Verificaoms si ya tenemos alguna versión de git
- Instalación de Git desde la fuente
- Configuración de Git


## Comprobamos los Requisitos previos
Es probable que Git ya esté instalado en el servidor Ubuntu 20.04, comprobamos con el siguiente comando:


```
git --version
```
 
Si obtiene un resultado similar al siguiente, significa que Git ya está instalado.

__Output__

```
git version 2.25.1
```

## Instalación de Git desde la fuente
instalamos el software necesario para Git todo se encuentra disponible en los repositorios predeterminados.

```
sudo apt update
sudo apt install libz-dev libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext cmake gcc
``` 
![](https://github.com/Alvaro-2002/Instalaci-n-de-Git-en-linux/blob/main/Imagenes/Captura%20de%20pantalla%20de%202021-11-03%2015-31-17.png)




Tras haber instalado las dependencias necesarias, cree un directorio temporal y vaya a él. Aquí es donde descargaremos nuestro tarball de Git.

```
mkdir tmp
cd /tmp
``` 

usamos el siguiente comando para descargar la versión 2.29.3

```
curl -o git.tar.gz https://mirrors.edge.kernel.org/pub/software/scm/git/git-2.29.3.tar.gz
``` 
![]()
