# Hola desde Git SSH

## Pasos para configurar Git local con github remoto

### Punto 1:

Primero debemos configurar nuestra cuenta de git con el correo y nombre de la cuenta de github usando los siguientes comandos:

```
# Comando para listar la configuracion de git en local:
git config --list 

# Con el siguiente comando configuramos el correo en nuestro git local
git config --global user.email "pepito@correo.com"

# Con el siguiente comando configuramos el nombre en nuestro git local
git config --global user.email "Pepito Perez"
```

### Punto 2:

Con el siguiente comando clonamos o hacemos una copia de un repositorio remoto a nuestro computador local:

```
git clone {url-repositorio}
```

### Punto 3:

Con este comando aprendemos a cambiarnos o movernos de una rama a otra rama.

```
git checkout {nombre-rama-a-ubicar}
```

### Punto 4: 

Con este comando vemos el listado de todas las ramas que existen:

```
git branch
```

### Punto 5: 

Con este comando actualizamos las ramas que existen en el repositorio remoto para poder movernos entre las ramas en nuestra computadoras

```
git fetch --all
```

### Punto 6:

Con este comando podemos identificar a que repositorio remoto esta conectado nuestro repositorio local.

```
git remote -v
```

### Punto 7

Con este apartado usaremos los siguientes comandos para trabajar en las 3 etapas que existen en nuestro git local:

1. Directorio de trabajo / Working Directory 
    ``` 
    git add .
    ```
    o
    ```
    git add {nombre-archivo}
    ```

    Nota: con el punto se envian todos los archivos y con el nombre solo envia el archivo que se quiere enviar

2. Area de confirmacion / Staging area

    ```
    git commit -m "Escribimos un mensaje"
    ```

3. Area de envio de los archivos confirmados / PUSH

    ```
    git push origin {nombre-rama}
    ```

### Punto 8

Con este comando podemos visualizar que cambios tenemos pendiente por agregar:

```
git status
```

NOTA: {Aqui escribre tu nombre y envia el cambio en una rama nueva}
