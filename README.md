#Wordpress + Composer

###Requisitos
* PHP >= 5.4
* Tener instalado composer https://getcomposer.org/

###Paso a paso

* Ejecutar el comando `composer install`
* Mover **wp-content/** del directorio **wp/**
* (Para apache2) Modificar **.haccess** con el nombre del dominio a usar.
* Crear archivo **.env** con la estructura de **.env.example**
* Ejecutar en el navegador para hacer la instalación.