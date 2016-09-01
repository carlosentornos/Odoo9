#1.- Instalación.
Desde la página web oficial podemos descargarnos la última versión de Odoo, en nuestro caso, **la 9c**, del 08 de agosto de 2016. Podremos seleccionar los distintos sistemas operativos disponibles para instalar Odoo: **MS Windows, GNU/Linux, así como el código fuente.**

A continuación mostraremos los diferentes tipos de instalación:

##1.1.- Mediante Uso de paquetes EXE (MS Windows) / DEB (GNU/Linux).
###1.1.2.- MS Windows.
Descargado el fichero  **"odoo_9.0c.latest.exe"** lo ejecutaremos en modo administrador y seguiremos las instrucciones del asistente de instalación (en inglés y/o francés), aceptaremos los términos y condiciones, y tendremos la siguiente ventana en nuestro escritorio:

![odoo_install_win_.png](./images/odoo_install_win_.png "Asistente Instalación de Odoo")

El asistente nos indica de que hay tres tipos de instalación de los componentes necesarios:
1. *All In One* (todo en uno), opción seleccionada por defecto.
2. *Server Only*, si queremos Odoo únicamente.
3. *Custom*.

Nosotros seleccionaremos "All In One" por lo que necesitaremos 560 MB libres de espacio en disco, una vez que aceptemos y cliquemos en siguiente será el momento de configurar nuestra conexión al motor de la Base de Datos PostgreSQL, por defecto el asistente tendrá los siguientes valores introducidos:

| Campo | Valor |
|:--------:|:--------:|
| Hostname | localhost |
| Port | 5432 |
| Username | openpg |
| Password | openpgpwd |

## Referencias
+ [Página Oficial Odoo.](https://www.odoo.com/es_ES/)

+ [Odoo install packages](https://www.odoo.com/documentation/9.0/setup/install.html#setup-install-packaged)