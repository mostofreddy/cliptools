Cliptools
=========

Cliptools es un mini framework que contiene herramientas para facilitar la creacion de aplicaciones PHP para correr por consola

Versión
-------
v0.1.0

Build Status
------------

[![Build Status](https://travis-ci.org/mostofreddy/cliptools.png?branch=master)](https://travis-ci.org/mostofreddy/cliptools)

Features
--------

* Recuperar los valores de entrada de un script por consola (script.php -v --key=value)

Licencia
-------
Software bajo licencia [MIT](http://opensource.org/licenses/mit-license.php)

Instalación
-----------

### github

    cd /var/www
    git clone git@github.com:mostofreddy/clip.git

### composer

    "require": {
        "php": ">=5.3.0",
        "mostofreddy/cliptools": "0.*",
    }

Ejemplos / Demos
----------------
En la carpeta [samples](https://github.com/mostofreddy/clip/tree/master/samples) se pueden encontrar ejemplos de uso

Tests
-----

    phpunit --configuration tests/phpunit.xml
