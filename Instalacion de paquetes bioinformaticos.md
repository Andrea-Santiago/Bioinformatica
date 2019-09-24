# Instalción de paquetes bioinformáticos en ubuntu 17.10
## 1.- Gedit 
En Ubuntu 17.10  el paquete Gedit  ya se encuentra instalado por defecto, para verificarlo, introducir el siguiente comando en la terminal:

``
$ gedit --version
``

Con esto se mostrará en la terminal  tanto el nombre del paquete como la versión instalada.

## 2.- Python 3.5.3
Para su instalación es necesario introducir el siguiente comando en la terminal:

``
$ sudo apt install python3.6
``

Para verificar que se ha instalado python 3.5.3, introducir:

``
$ python3 --version
``

Con esto se mostrará en la terminal  tanto el nombre del paquete como la versión instalada.

## 3.- Biopython
Para comenzar la intalación, introducir:

``
$ sudo apt-get update
``

Esperar a que finalice, he introducir el siguiente comando:

``
$ sudo apt-get install python3-biopython
``

Con este comando iniciará la intalación de biopython y automáticamente terminara la instalación del mismo.

## 4.- Git
Para la intalación de este paquete solo es necesario introducir el siguiente comando en la terminal:

``
$ sudo apt install git
``

## 5.- Bioperl
Para instalar este paquete solo basta con introducir el siguiente comando:

``
$ sudo apt-get install bioperl
``

## 6.- Bio::seq
Bio::seq es un módulo de Bioperl, por tal motivo, es necesario tener instaldo antes a Bioperl para después solo introducir el siguiente comando para que de inicio  la instalación de este módulo.


``
$ cpan Bio::seq
``

Nota: si se tienen dudas, se recomienda consultar la siguiente página: [Intalación de Bio::seq](http://www.bioinformatics-made-simple.com/2014/09/how-do-i-install-and-use-bioperl-on.html)

## 7.- Anaconda
Para su instalación, es necesario correr en la terminal los siguientes comando en el siguiente orden:

``
$ cd /opt
``

``
$ sudo wget http://repo.continuum.io/archive/Anaconda3-4.0.0-Linux-x86_64.sh
``

``
$ bash Anaconda3-4.0.0-Linux-x86_64.sh
``

Para finalizar, ya solo escribir el siguiente comando y dar enter:

``
$ export PATH=~/anaconda3/bin:$PATHconda--version
``

Nota: si se tienen dudas, se recomienda consultar la siguiente página: [Intalación de Anaconda](http://linuxpitstop.com/install-anaconda-miniconda-conda-on-ubuntu-centos-linux/)

## 8.- FASTQC
Para la instalación de este paquete, solo es necesaro ejecutar el siguiente comando en la terminal:


``
$ sudo apt-get install fastqc
``

## 9.- CUTADAPT
La instalación de este paquete se lleva a cabo con  el paquete Conda, por lo tanto, solo es nesesario introducir el siguiente comando:


``
$ conda install -c bioconda cutadapt
``

## 10.- TRIMMGALORE
La instalación de este paquete es de igual forma muy sencillo, pués solo basta con ejecutar el siguiente comando en la terminal:


``
$ conda install -c bioconda trim-galore
``

## 11.- Trimmomatic
Nuevamente, para este paquete se necesita ejecutar los siguientes comandos respetando el siguiente orden:


``
$ sudo apt-get update -y
``

``
$ sudo apt-get install -y trimmomatic
``

## 12.- SPAdes
Para poder instalar este paquete solo es necesario ejecutar el siguiente comando en la terminal:


``
$ sudo apt install spades
``

## 13.- Velvet
La instalación de este paquete  requiere ejecutar los siguientes dos comandos:


``
$ sudo apt-get update
``

Después de que se haya terminado de ejecutar el comando anterior, ejecutar el siguiente y esperar a que este termine.

``
$ sudo apt-get install velvet
``

## 14.- C-shell
Para instalar este paquete, solo es necesario ejecutar el siguiente comando en la terminal y esperar a que este termine:

``
$ udo apt-get install tcsh
``

## 15.- MUMMER
Nuevamente, la instalación de este paquete solo requiere ejecutar el siguiente comando y esperar a que este finalice.

``
$ conda install -c bioconda mummer
``

## 16.- Cpp4.7
De igual forma, solo es necesario ejecutar el siguiente comando para poder instalar este paquete:

``
$ sudo apt-get install gcc-4.7
``

## 17.- Quast
De forma similar que el paquete anterior, solo se necesita ejecutar el siguiente comando para la instalación de este:

``
$ conda install -c bioconda quast
``

## 18.- Samtools
Finalmente, la instalación de este paquete requiere de igual forma que los anteriores, ejecutar el siguiente comando y esperar a que este finalice:

``
$ conda install -c bioconda samtools
``

## 19.- Programa R y Rstudio
La instalación de este programa requiere varios comandos, los cuales  se han dividido en diferentes pasos.

Paso 1. Actualizar el sistema: para lograr esto, es necesario ejecutar en el mismo orden los siguientes comandos y esperar a que termine uno para poder inicar con el otro comando.

``
$ sudo apt update
``

``
$ sudo apt -y upgrade
``

Paso 2. Instalar R en ubuntu: Para poder llevar a cabo la instalación del programa solo es necesario ejecutar el siguiente comando en la terminal

``
$ sudo apt -y install r-base
``

Al finalizar este comando, la instalación de este programa habrá  terminado, sin embargo, si se desea instalar Rstudio se suguiere continuar con los siguientes pasos.

Paso 3. Descargar e instalar Rstudio
Antes de instalar Rstudio, es necesario descargarlo y eso se logra ejecutando el siguiente comando:

``
$ wget https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.2.1335-amd64.deb
``

Finalmente, solo es necesario ejecutar el siguiente comando para realizar la instalación de Rstudio.

``
$ sudo dpkg -i rstudio-1.2.1335-amd64.deb
``

Paso 4. Comprobar que la instalación ha sido correcta.  

``
$ rstudio
``

Con este comando se habrirá el programa Rstudio, es caso de haber realizado correctamente la instalación del mismo.
