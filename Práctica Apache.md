# Práctica Apache

## APARTADO 1
[Imágen versión Ubuntu](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/Imagenes%20Apache/Captura%20de%202026-10-07%2009-23-26.png)

## APARTADO 2
**¿Qué paquetes adicionales se han instalado como dependencias?**

[Imágen paquetes](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/Imagenes%20Apache/Captura%20de%202026-10-07%2009-28-15.png)

## APARTADO 3

### APARTADO 3.3
[Imágen Apache default page](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/Imagenes%20Apache/Captura%20de%202026-10-07%2009-50-45.png)

### APARTADO 3.4
**¿Qué diferencia hay entre los perfiles Apache, Apache Full y Apache Secure?**

## APARTADO 4

|Comando                        | Función                                      |
|-------------------------------|----------------------------------------------|
|sudo systemctl start apache2   |Inicia Apache                                 |
|sudo systemctl stop apache2    |Para Apache                                   | 
|sudo systemctl restart apache2 |Reinicia Apache                               |
|sudo systemctl reload apache2  |Recarga Apache                                |
|sudo systemctl enable apache2  |Inicia Apache automáticamente                 |
|sudo systemctl disable apache2 |Desactiva arranque automático                 |
|apache2ctl configtest          |Comprueba la configuración                    |
|apache2ctl -S                  |Muestra los host cargados                     |
|apache2ctl -M                  |Lista módulos cargados                        |
|a2enmod / a2dismod             |Activa y desactiva módulos                    |
|a2ensite / a2dissite           |Activa y desactiva sitios                     |
|a2enconf / a2disconf           |Activa y desactiva fragmentos de configutación|

**¿Cuándo conviene usar reload en lugar de restart?**
Sí, porque no corta conexiones

## APARTADO 5

|Ruta                                         | Descripción                                |
|---------------------------------------------|--------------------------------------------|
|/etc/apache2/apache2.conf                    | Configuración Apache                       |
|/etc/apache2/ports.conf                      | Puertos de escucha de Apache               |
|/etc/apache2/sites-available/                | Sitios disponibles de Apache               |
|/etc/apache2/sites-enabled/                  | Sitios activos                             |
|/etc/apache2/mods-available/ y mods-enabled/ | Módulos disponibles y activos              |
|/etc/apache2/conf-available/ y conf-enabled/ | Configuración disponible y activo          |
|/etc/apache2/envvars                         | Variables de entorno                       |
|/var/www/html/                               | Dirección predeterminada                   |
|/var/log/apache2/access.log                  | Registros de Acceso                        |
|/var/log/apache2/error.log                   | Registros de Error                         |



[Captura contenido /etc/apache2](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/Imagenes%20Apache/Captura%20de%202026-10-07%2010-13-46.png)
