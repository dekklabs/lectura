# Clonar del repositorio de github en la carpeta www de laragon

## Ingresar a la carpeta cambicash

- Crear la base de datos con el nombre cambicash
- Abrir el archivo db_16122020.sql que se encuentra en la carpeta backup$ que está en la raíz del proyecto y ejecuta
## en Mysql
    - use cambicash
    - run script

## Instalar dependencias js
- Ejecutar ``npm install``

## Instalar dependencias PHP
- Ejecutar ``composer install``

## Editar el archivo .env
en la raíz del proyecto se encontrará un archivo llamado .envvv, deberás renombrar el nombre a ".env"
y dentro del archivo editar las siguientes lineas de código

```
DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=cambicash
DB_USERNAME=root
DB_PASSWORD=123456
```

donde username será el nombre de tu usuario de mysql y tu password en el caso de tengas uno

## Iniciar proyecto

ejectar el comando ``npm run hot``
