# Web2py Admin Plus


Admin Plus es un plugin para Web2py que proporciona una interfaz administrativa fácil de usar para la gestión de sus datos.

Dependencias
--------------

Admin plus requiere:

- Python 2.7.x
- Web2Py 2.x
- Firefox 20+, Chrome 20+


## Instalacion

1. Descarga e instala el plugin
2. luego ve a `127.0.0.1:8000/<app>/plugin_admin_plus/install`
3. Opten los permisos con `plugin_admin_plus_superuser` en `127.0.0.1:8000/<app>/appadmin/insert/db/auth_membership`
4. ! Listo ! ahora puedes iniciar sesion `127.0.0.1:8000/<app>/plugin_admin_plus/index`

NOTA: sustituye `<app>` por el nombre de tu aplicacion

### Donaciones

Puedes ayudar enviando tus donaciones con bitcoin ala siguiente direccion :

##### `1K3Yx6weidrtShdAiqFPbiTvsp7r74QS7o` ![Screenshot](http://bitcoin.org/img/logotop.svg)


# Screenshots

### index

![Screenshot](https://lh5.googleusercontent.com/-LiE0dI7I7CQ/UsjHLe3IyTI/AAAAAAAAAEY/joZXKOFJVrg/w873-h491-no/Screenshot+from+2014-01-04+17%253A49%253A19.png)


### list

![Screenshot](https://lh3.googleusercontent.com/-FW0Ju60dpGM/UsSvmKXXSSI/AAAAAAAAAVA/0PxQesaI4kw/w873-h491-no/07-lista3.png)


### edit

![Screenshot](https://lh4.googleusercontent.com/-WmbChzRuovA/Usnv-uLSVXI/AAAAAAAAAX8/12e5GclFs-U/w905-h509/Screenshot+from+2014-01-05+18:32:35.png)


## Configuration

En el controlador plugin_admin_plus.py puedes hacer tus configuraciones


Configuracion de paginacion :
   
   `optimizar_paginacion = True`
   
   `settings.items_per_page = 6`

si `optimizar_paginacion` es establecido como False, se usara la paginacion interactiva, es conveniente cuando se cuenta con menos de mil registros en una tabla, de lo contrario el rendimiento sera afectado considerablemente.

   
Menu extra:

-> (ejemplo)

    settings.extra_sidebar_title = 'Titulo'
    settings.extra_sidebar = [ LI(A(I(_class="fa fa-angle-right"), ' bitcoin', _href="http://bitcoin.com")), \
                               LI(A(I(_class="fa fa-angle-right"), ' web2py', _href="http://web2py.com")), \
                               LI(A(I(_class="fa fa-angle-right"), ' github', _href="http://github.com")), \
                        ]



Reportar Bugs
-----------------------------------------
Por favor reporta los bugs en https://github.com/pyner/admin_plus/issues


Licencia
-----------------------------------------
Licenciado bajo LGPLv3


Contribuciones
-----------------------------------------
Contribuciones y Feedbacks son bienvenidos.


Informacion del autor
-----------------------------------------
Samuel Bonilla <pythonners@gmail.com>

* http://github.com/pyner
