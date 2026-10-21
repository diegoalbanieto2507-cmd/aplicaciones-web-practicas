# Práctica: Instalación de MariaDB y PHP en Ubuntu 24.04 #

## Diego Alba ##

### 2ºSMR ###

## Apartado 1 ##

[Captura de la respuesta de systemctl is-active apache2.](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/Apache-activo.png)

## Apartado 2 ##

[Captura de la versión](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/Version-mariadb.png)

## Apartado 3 ##

[Captura del estado del servicio y de la entrada en MariaDB](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/Sudo-Mariadb.png)

## Apartado 4 ##

|**Comando**                    |**Función**                                      |
|-------------------------------|-------------------------------------------------|
|sudo systemctl start mariadb   |Arranca el servicio                              |
|sudo systemctl stop mariadb    |Detiene el servicio                              |
|sudo systemctl restart mariadb |Reinicia el servidor                             |
|sudo systemctl status mariadb  |Muestra su estado                                |
|sudo systemctl enable mariadb  |Lo arranca automáticamente al encender el equipo |

## Apartado 5 ##

[Captura del error](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/Error2002.png)

[Recuperacion](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/Recuperacion%20del%20error.png)

**Si WordPress no pudiera conectar con la base de datos, ¿qué dos comandos de este apartado usarías
para saber si el problema es que MariaDB está parado?**

1. sudo systemctl start mariadb

2. sudo systemctl restart mariadb

## Apartado 6 ##

[Captura de php -v, de los módulos y de la página info.php.](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/mariadb/PHP-VERSION.png)

**¿Por qué es peligroso dejar info.php en un servidor real?** Porque esa información la pueden ver desde fuera

**¿Para qué sirve el paquete php-mysql?** Permite a PHP hablar con MariaDB


