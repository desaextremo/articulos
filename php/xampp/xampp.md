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
