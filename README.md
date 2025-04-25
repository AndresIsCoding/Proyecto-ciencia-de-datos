# Proyecto-ciencia-de-datos
## Importante
- Al inicio del cuaderno estan las importaciones y las librerias necesarias para el funcionamiento del programa, por ende es necesario ejecutar las celdas en orden.
- Es necesario crear un archivo .env dentro del directorio Proyecto-ciencia-de datos con la siguiente estructura:

        DB_USER = [usuario de postgres]
        DB_PASSWORD = [Contraseña de postgres]
        DB_HOST = [host asignado, generalmente es localhost]
        DB_PORT = [puerto asignado, generalmente es el 5432]
        DB_NAME = [nombre de la base de datos en local]```
        
  Con el fin de que el código dentro del cuaderno jupyter ejecute correctamente, este archivo no debe ser subido al repositorio.
- Los cursores van a generar cambios en la base de datos, al ser ejecutados por segunda vez generan errores.
## Cambios a las tablas
- En ciudad:
  - ciudad_id -> id
  - nombre -> nombre_ciudad
- En departamento:
  - departamento_id -> id
  - nombre -> nombre_departamento