# Instalacion y configuracion de XAMPP

* Descargar instalador para linux [apachefriends](https://www.apachefriends.org/download.html)

<p align="center">
  <img src="images/xampp1.png" alt="instalacion en Linux" title="instalacion en Linux" />
</p>

1 Instalar archivo .run

```shell
sudo ./<archivo.run>
```

2 También puedes descargar tu versión preferida desde la terminal.

```
# Xampp con php 7.2
wget -r https://www.apachefriends.org/xampp-files/7.4.8/xampp-linux-x64-7.4.8-0-installer.run

# Xampp con php 7.3
wget -r https://www.apachefriends.org/xampp-files/7.3.20/xampp-linux-x64-7.3.20-0-installer.run

# Xampp con php 7.4
wget -r https://www.apachefriends.org/xampp-files/7.4.8/xampp-linux-x64-7.4.8-0-installer.run

wget -r https://www.apachefriends.org/xampp-files/8.0.7/xampp-linux-x64-8.0.7-0-installer.run
```

* Una vez lo tengas descargado debes concederles permisos, si lo has descargado desde la web lo puedes localizar en tu carpeta de descargas, si fue a través de «wget», en…

```shell
/home/tu-usuario/www.apachefriends.org/xampp-files/<nro version>
```

3 Conseder permisos con chmod: Acceder a la ubicacion desde la consola y conceder permisos.

```shell
  chmod 755 xampp-linux-<nro version>-installer.run
```
4 Instalar 
```shell
sudo ./xampp-linux-<nro version>-installer.run
```
Por ejemplo para la version 8.0.7-0 de 64 bits, el archivo de instalacion se llama `xampp-linux-x64-8.0.7-0-installer.run`

* Arrancar xampp
```shell
  $ sudo /opt/lampp/lampp start
```
* Detener xampp
```shell
  $ sudo /opt/lampp/lampp stop
```
* Arrancar xampp
```shell
  $ cd /opt/lampp
  $ sudo ./manager-linux-x64.run
```
