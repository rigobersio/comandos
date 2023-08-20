# Comandos Tipo Unix

## Comandos Frecuentes

### cd
Cambia el directorio actual.

| Comando | Opción |    Argumento    |
| ------- | ------ | --------------- |
| cd      |        | ruta_directorio |
|         | ../    |                 |
|         | ../../ |                 |

Ejemplo:
- `cd mi_carpeta` cambia al directorio "mi_carpeta".
- `cd ..` retrocede un directorio.
- `cd ../` es lo mismo que el anterior.
- `cd ../../` retrocede dos directorios. No hay ningún espacio ../../

### ls
Lista carpetas y archivos en el directorio actual.

| Comando | Opción | Argumento |
| ------- | ------ | --------- |
| ls      | -a     |           |
|         | -l     |           |
|         | -all   |           |

Opción:
- `-a` muestra los directorios y archivos ocultos.
- `-l` muestra los detalles en formato largo.
- `-all` muestra todos, incluidos los ocultos.

Ejemplo:
- `ls` muestra los archivos y carpetas.
- `ls -a` muestra todos, incluidos los ocultos.
- `ls -l` muestra los detalles de archivos y carpetas.
- `ls -all` muestra todos, incluidos los ocultos con detalles.

...


### echo
Muestra un texto en la terminal.

| Comando | Opción | Argumento |
| ------- | ------ | --------- |
| echo    |        | texto     |

Ejemplo:
- `echo "Hola, mundo"` muestra "Hola, mundo".

### mkdir
Crea un nuevo directorio.

| Comando | Opción |     Argumento     |
| ------- | ------ | ----------------- |
| mkdir   |        | nombre_directorio |

Ejemplo:
- `mkdir nueva_carpeta` crea la carpeta "nueva_carpeta".

### rmdir
Elimina un directorio vacío.

| Comando | Opción |     Argumento     |
| ------- | ------ | ----------------- |
| rmdir   |        | nombre_directorio |

Ejemplo:
- `rmdir antigua_carpeta` elimina la carpeta "antigua_carpeta".

### touch
Crea un nuevo archivo vacío.

| Comando | Opción |   Argumento    |
| ------- | ------ | -------------- |
| touch   |        | nombre_archivo |

Ejemplo:
- `touch nuevo_archivo.txt` crea el archivo "nuevo_archivo.txt".

### rm
Elimina un archivo.

| Comando | Opción |   Argumento    |
| ------- | ------ | -------------- |
| rm      | -f     | nombre_archivo |

Opción:
- `-f` fuerza la eliminación.

Ejemplo:
- `rm archivo.txt` elimina el archivo "archivo.txt".
- `rm -f archivo.txt` elimina forzadamente.

### head
Muestra las primeras líneas de un archivo.

| Comando | Opción |   Argumento    |
| ------- | ------ | -------------- |
| head    | -n     | nombre_archivo |

Opción:
- `-n` especifica el número de líneas.

Ejemplo:
- `head archivo.txt` muestra las primeras líneas del archivo.
- `head -n 5 archivo.txt` muestra las primeras 5 líneas.

### nano
Abre un editor de texto en la terminal.

| Comando | Opción |   Argumento    |
| ------- | ------ | -------------- |
| nano    |        | nombre_archivo |

Ejemplo:
- `nano archivo.txt` abre el archivo en el editor nano.

### pwd
Muestra el directorio actual.

| Comando | Opción | Argumento |
| ------- | ------ | --------- |
| pwd     |        |           |

Ejemplo:
- `pwd` muestra la ruta del directorio actual.

### mv
Mueve o cambia el nombre de un archivo.

| Comando | Opción |   Argumento    |
| ------- | ------ | -------------- |
| mv      |        | origen destino |

Ejemplo:
- `mv archivo.txt carpeta/` mueve "archivo.txt" a "carpeta/".
- `mv archivo.txt nuevo_nombre.txt` cambia el nombre.

## abrir archivos con editores de código.

|  Comando  | Opción |                  Argumento                   |        Nombre         |
| --------- | ------ | -------------------------------------------- | --------------------- |
| notepad++ |        | archivo.txt                                  | Notepad++             |
| nano      |        | archivo.txt                                  | Nano                  |
| vim       |        | archivo.txt                                  | Vim                   |
| neovim    |        | archivo.txt                                  | Neovim                |
| sublime   |        | archivo.txt                                  | Sublime Text          |
| code      |        | archivo.txt                                  | Visual Studio Code    |
| other     |        | archivo.txt                                  | Otro Editor de Código |
|           |        | /home/usuario/Documentos/archivo.txt (Linux) |                       |
|           |        | C:\codeo\archivo.txt (Windows)               |                       |

