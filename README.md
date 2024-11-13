# Manual de Instalacion-owncloud


1. Actualización de la máquina.

 ``
sudo apt update
``
<img src="imagen sudo apt update." alt="Descripció de la imatge">




Y después tienes que poner

``
sudo apt upgrade
``



2.Una vez hecho la actualizaion de la maquina, pasamos a la instalacion del servidor web llamado apache2

``
sudo apt install -y apache2
``

3. Instalaremos la base de dadas

``
sudo apt install -y mysql-server
``

4. Instalar las librerias de php. Es un lenguaje principal que usan las apps

``
sudo apt install -y php libapache2-mod-php
``

Seguido de este comando has de poner esto:

``
sudo apt install -y php-fpm php-common php-mbstring php-xmlrpc php-soap php-gd php-xml php-intl php-mysql php-cli php-ldap php-zip php-curl
``

5. Una vez hecho todos estos pasos, reiniciamos nuestro apache2 con:

``
sudo systemctl restart apache2
``
