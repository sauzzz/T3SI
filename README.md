# EJERCICIO 4. Partiendo de tu directorio de inicio, realiza cada uno de los siguientes apartados:

- Haz que tu directorio de trabajo actual sea el directorio padre de tu directorio de inicio.

Para cambiar de un directorio a otro usamos el siguiente comando:

~~~
cd
~~~
Y para colocarse en el directorio padre añadimos:

~~~
cd /home
~~~

- Visualiza la ruta de tu directorio de trabajo actual.

Usamos el siguiente comando:
~~~
pwd
~~~

> Nota: Nos mostrará la ruta del directorio de trabajo actual:

~~~
/Users/sauz
~~~

- Obtén un listado de todos los ficheros/directorios que cuelgan de tu directorio de trabajo actual.

Usamos el siguiente comando:

~~~
ls
~~~
> Nota: La ejecución del comando nos mostrará un listado:

~~~
ls
$RECYCLE.BIN	Thumbs.db	desktop.ini
~~~

- Realiza un listado recursivo de tu directorio de inicio.

Para mostrar un listado usamos el comando:
~~~
ls
~~~

Y para que el listado sea recursivo añadimos:

~~~
ls -r
~~~

> Nota: El comando -r añadirá todos los subdirectorios que contiene el directorio.


- Obtén la ayuda del comando passwd.

Usamos el siguiente comando:

~~~
passwd -h
~~~

> Nota: El comando -h nos mostrará la ayuda del comando indicado.

> También podemos usar -help.

- Obtén la fecha y la hora del sistema.

Usamos el siguiente comando:

~~~
date
~~~

> Nota: El comando nos mostrará la fecha y hora del sistema:
~~~
jueves, 24 de noviembre de 2022, 09:35:43 CET
~~~

- Usando un solo comando posiciónate en tu directorio de inicio.

Usamos el siguiente comando:

~~~
cd
~~~

- Crea un fichero materias que contenga el nombre de las materias en las que te has matriculado (cada una en una línea distinta).

Para crear un fichero usamos el siguiente comando:

~~~
cat > (nombre del fichero)
~~~
Una vez introducido el comando añadimos los datos linea por linea:

~~~
cat > materias
Lenguaje de marcas
Programación
Sistemas Informáticos
Bases de datos
Entornos de desarrollo
~~~

> Nota: Para acabar de introducir datos usamos "Ctrl + D"

- Con un solo comando, crea dos directorios grado y lru.

Para crear un directorio usamos el comando:

~~~
mkdir (nombre directorio)
~~~

Para crear otro directorio en la misma línea de comando tenemos que añadir el nombre del segundo directorio:

~~~
mkdir grado lru
~~~

> Nota: Se crearán 2 directorios.


- Usando un solo comando, mueve tu fichero materias para que cuelgue de tu directorio grado pero con el nombre asignaturas.

Usamos el siguiente comando:

~~~
mv materias grado/asignaturas
~~~

> Nota: Lo que estamos haciendo con ese comando moverlo al directorio grado y cambiarle el nombre a asignaturas (grado/asignaturas)

- Visualiza los ficheros/directorios de tu directorio de trabajo actual y responde a la siguiente cuestión: ¿dónde está tu fichero materias?

Para visualizar los ficheros usamos el siguiente comando:

~~~
ls
~~~

El fichero materias se ha movido a la carpeta /grado y se le ha cambiado el nombre a asignaturas.

- Posiciónate en tu directorio grado.

Para posicionarse en un directorio usamos el siguiente comando y la ruta del directorio:

~~~
cd Desktop/grado
~~~

- Elimina el fichero asignaturas.

Para eliminar el fichero usamos:

~~~
rm asignaturas
~~~

- Sube al directorio de inicio.

Usamos el siguiente comando:

~~~
cd
~~~

- Con un solo comando elimina los directorios creados en el paso i.

Nos posicionamos en la carpeta padre:
~~~
cd /Desktop
~~~

Y usamos el siguiente comando:

~~~
rmdir grado lru
~~~
