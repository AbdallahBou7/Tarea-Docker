# Ejercicio 4 -Docker Compose

> Realizado por Abdallah Bouallag y Alejandro Luis
> 

## **Crear el archivo `docker-compose.yaml`**

- Primero Creamos una nueva carpeta y dentro de ella creamos el nuevo archivo

```powershell
cd docker-htop
```

![image.png](image.png)

- Aquí tenia que instalar `htop` dentro del contenedor manualmente

```yaml
services:
	htop:
		image: alpine
		container_name: htop
		stdin_open: true
		tty: true
		command:["sh", "-c", "apk add --no-cache htop && htop"]
```

![image.png](image%201.png)

## **Desplegar la aplicación `htop` utilizando Docker-Compose.**

- Ejecuto este comando dentro de la carpeta

```powershell
docker compose up -d
```

![image.png](image%202.png)

- Luego accedo al htop dentro del contenedor

![image.png](image%203.png)

## Explicación de `htop`

- `htop` es una aplicación de **monitorización de procesos** en sistemas Linux.
- Es una versión mejorada del comando `top`, con una interfaz más amigable, colores y opciones interactivas.
- **Características principales:**
    - Muestra el uso de CPU, memoria y procesos en ejecución.
    - Permite ordenar y filtrar procesos en tiempo real.

## GitHub Projects

- Así quedaría el GitHub Project por el momento.

![image.png](image%204.png)

![image.png](image%205.png)