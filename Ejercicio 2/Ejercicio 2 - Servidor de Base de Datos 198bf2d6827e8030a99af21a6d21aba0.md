# Ejercicio 2 - Servidor de Base de Datos

> Realizado por Abdallah Bouallag y Alejandro Luis
> 

- Abrimos **Docker Desktop**.
- Vamos a la sección **"Imagenes"**.
- Buscamos `mariadb`.
- Si no tenemos la imagen , la descargamos ejecutando en la terminal:

![image.png](7be7d87c-7b59-4be2-8d24-57d1e0dcf4f0.png)

- Así se vería después de acabar la descarga de la imagen.

![image.png](image.png)

- Creamos y ejecutamos un contenedor con MariaDB con estos datos

![image.png](image%201.png)

- Iniciamos el contenedor, se debería ver algo así

![image.png](image%202.png)

- Después de introducir los datos en DBeaver, probé la conexión y como funciono, acepte y se creo la conexión.

![image.png](image%203.png)

- Ahora cree una base de datos llamada prueba con un campo llamado nombre

![image.png](image%204.png)

- Primero buscamos el contenedor, lo detenemos y luego lo borramos

![image.png](image%205.png)

![image.png](image%206.png)

![image.png](image%207.png)

- Después de borrar el contenedor revisamos el apartado volúmenes y si lo hemos hecho de la forma correcta debería verse algo así

![image.png](image%208.png)

- Creamos otro contenedor con el mismo volumen con estos datos y lo arrancamos

![image.png](image%209.png)

![image.png](image%2010.png)

![image.png](image%2011.png)

- Intentamos borrar la imagen de mariadb y como era de esperar al estar usándose nos da este mensaje

![image.png](image%2012.png)

- Como ultimo paso borramos todo

![image.png](image%2013.png)

![image.png](image%2014.png)

![image.png](image%2015.png)

## GitHub Projects

- Así quedaría el GitHub Project por el momento.

![image.png](image%2016.png)

![image.png](image%2017.png)