Para UBUNTU Xenial
Ejecutar:
sudo nano /etc/apt/sources.list

Y agregar las siguientes lineas al final del archivo:
```
deb http://qgis.org/ubuntugis xenial main
deb-src http://qgis.org/ubuntugis xenial main
deb http://ppa.launchpad.net/ubuntugis/ubuntugis-unstable/ubuntu xenial main
```

Guardar, salir y ejecutar:
```
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-key 089EBE08314DF160
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 00000000
sudo apt-get update
sudo apt-get install qgis python-qgis qgis-plugin-grass
sudo apt-get install postgresql-9.x-postgis-scripts
```
