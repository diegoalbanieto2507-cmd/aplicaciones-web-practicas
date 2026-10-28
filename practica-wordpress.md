# Instalación de Wordpress

## APARTADO 1

### APARTADO 1.3

[**Captura de la conexión SSH y del resultado de los dos comandos.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/conexi%C3%B3n.ssh)

**¿Qué dos "puertas" (programas y puertos) usas para trabajar con el servidor en esta práctica y para qué sirve cada una?**

Apache2 y mariadb

## APARTADO 2

### APARTADO 2.2

[**Captura las salidas de estos comandos.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/salidas%202.2.png)

### APARTADO 2.3

[**Captura de los comandos y de la página de Apache en tu navegador**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/navegador_2.3.png)

**¿Qué diferencia hay entre desactivar un sitio con a2dissite y borrar sus ficheros? ¿Por qué ahora ves la página por defecto de Apache y antes veías sitio1?**

Porque solo hay un sitio activo

## APARTADO 3
[**Captura de las tres órdenes (sin la contraseña a la vista) y de la entrada con wp_user.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/cap_Apartado3.png)

**¿Por qué crees que WordPress usa su propio usuario wp_user con permiso solo sobre su base y no el usuario root de MariaDB?**

Por mayor privacidad

## APARTADO 4

### APARTADO 4.2

**Explica qué hace cada uno de los comandos que acabas de ejecutar.**

1. **Sudo apt install wget -y:** Descarga archivos
2. **cd /tmp:** Entra al tmp
3. **wget https://wordpress.or/latest.tar.gz** Descarga archivos de wordpress
   
1. **ls wordpress:** Ve el contenido de wordpress
2. **sudo rm /var/www/html/index.html**
3. **sudo cp -a /tmp/wordpress/. /var/www/html/**
4. **rm -r /tmp/wordpress /tmp/latest.tar.gz**
5. **ls /var/www/html**
   Mete a wordpress en /var/www/html

### APARTADO 4.3

[**Captura de la carpeta de WordPress y de sus permisos.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/permisos_y_carpeta_wordpress_4.3.png)

## APARTADO 5

 [**Captura de las pantallas 3 y 5 (con la contraseña tapada) y del escritorio de WordPress una vez dentro.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/Inicio-sesion-wordpress.png)

**¿Qué partes de la instalación has hecho en la terminal y cuáles en el navegador? ¿Por qué el servidor no necesita tener interfaz gráfica?** 

En la terminal he descargado los archivos de wordpress y en el navegador solamente hay que poner la ip e iniciar sesión

## APARTADO 6

[**Captura de la entrada publicada en la web y del resultado de SHOW TABLES.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/TABLA_ShowTables.png)

**¿Dónde guarda WordPress las entradas que escribes: en ficheros del servidor o en la base de datos? ¿Cómo lo has comprobado?**

En la base de datos ya que lo almacena y busca que esté correctamente

## APARTADO 7

[**Captura de las dos líneas dentro de wp-config.php y del resultado de php -l.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/CAP_APARTADO7.png)

## APARTADO 8

### APARTADO 8.2

[**Captura de la configuración de Apache, de la dirección "bonita" de una entrada y del tamaño máximo de subida.**](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/Inicio-sesion-wordpress.png)

**¿Por qué las direcciones "bonitas" dan error 404 si Apache no tiene permitido leer el fichero .htaccess?**

Porque no tiene internet

## APARTADO 9

[RECUPERACION](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/Recuperacion_9png)

[ERROR](https://github.com/diegoalbanieto2507-cmd/aplicaciones-web-practicas/blob/main/carpeta-wordpress/Recuperacion_9png)

**Cuando WordPress muestra "Error al establecer una conexión con la base de datos", ¿qué dos cosas comprobarías y en qué orden?**

1.La ip
2.El ubuntu server
