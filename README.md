# CursoPostgreSQL. :elephant:
Un repositorio creado para ser usado como apoyo en un curso de Postgresql.
## ¿Qué es PostgreSQL?
PostgreSQL es un sistema de bases de datos relacionales open-source. Esta es una de las bases de datos mas usadas por aplicaciones web, moviles y analiticas.

### Historia.
El proyecto POSTGRES, dirigido por el Profesor Michel Stonebreaker, fue financiado por la Agencia de Proyectos de Investigación Avanzados de Defensa (DARPA), la Oficina de Investigación del Ejercito (ARO), la Fundacion Nacional de Ciencia (NSF), y ESL, Inc. (Sistemas de laboratorio Electromagneticos) en 1986.
Pero fue en 1996 cuando adopto el nombre PostgreSQL para reflejar la relación con el nombre POSTGRES y su nueva capacidad de SQL.
### Usos comunes de PostgreSQL.
1. Base de datos en LAPP.
   * LAPP significa: **Linux**, **Apache**, **PostgreSQL**, **PHP**. El cual es un stack bastante común.
2. Base de datos de uso general.
   * PostgreSQL es usado como base de datos transaccional por muchos, desde grandes empresas como startups
3. Base de datos Geoespacial.
   * Con la extencion de [PostGis](https://postgis.net/) es posible soportar un sistema de informacion geográfica o GIS, el cual es un entorno para recopilar, gestionar y analizar datos.
### Soporte de lenguajes.
PostgreSQL tiene soporte para algunos de los lenguajes de programación mas populares, como:
* Python.
* Java.
* C#
* C / C++
* Ruby.
* JavaScript (Node.js).
* Perl.
* Go.
* Tcl.
### ¿Quien usa PostgreSQL?
Muchas compañias han desarrollado productos usandolo. Algunas de ellas son Apple, Fujitsu, Red Hat, Cisco, Juniper Network, entre otras.
## Instalación.
Para este curso instalaremos 2 cosas PostgreSQL y DataGrip.
Para la inslación seguiremos el tutorial de [POSTGRESQL TUTORIAL](https://www.postgresqltutorial.com/postgresql-getting-started/install-postgresql/) donde podras encontrar un tutorial de instalacion para tu sistema operativo de elección (Windows, Linux o MacOS).
> [!IMPORTANT]
> Asegurate de [descargar el instalador](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads) desde la pagina oficial de PostgreSQL así como instalar la versión 16.1 la cual es la mas reciente.

En cuanto a DataGrip debemos descargalo desde la pagina de [JetBrains](https://www.jetbrains.com/es-es/datagrip/) este requiere una licencia, pero podemos acceder a esta de manera gratuita con el [GitHub Student Developer Pack](https://education.github.com/pack) el cual aparte de muchas herramientas para programar y aprender, incluye toda la biblioteca de JetBrains, y por consecuencia DataGrip.

> [!TIP]
> Si no tienes una cuenta de GitHub o aún no reclamas tu [GitHub Student Developer Pack](https://education.github.com/pack) puedes hacerlo en el link proporcionado con tu correo institucional.

## Teoria.
### Propiedades ACID.
Las propiedades ACID son cruciales ya que definen las transacciones de las bases de datos relacionales: Atomicidad, Consistencia, Aislamiento y durabilidad. A estas se le llaman ACID por sus iniciales en Ingles (Atomicity, Consistency, Isolation y Durability).
+ (A) Atomicidad: La transacción se debe completar o no se ejecutará.
+ (C) Consistencia: La base de datos debe permanecer consistente antes y despues de la transacción.
+ (I) Aislamiento: Multiples transacciones pueden ocurrir de manera independiente sin interferir.
+ (D) Durabilidad: Los cambios de una transaccion exitosa deben ocurrir incluso si el sistema falla.
### CRUD: Gestion de bases de datos.
CRUD es un acronico que une las iniciales de las cuatro operaciones en bases de datos.
+ Create (Crear).
+ Read o Retrive (Leer).
+ Update (Actualizar).
+ Delete o Destroy (Borrar).
Esto resume las funciones que un usuario necesita para crear y gestionar datos.
