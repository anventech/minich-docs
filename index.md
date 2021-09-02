# Introducción

Minich es una aplicación de mensajería para la línea de comandos que conecta Discord y Telegram.

## ¿Cómo conseguirla?

Puedes conseguir Minich desde su repositorio oficial: [anventech/minich](https://github.com/anventech/minich)

## ¿Cómo instalarla?

Puedes instalar Minich siguiendo cuidadosamente los siguientes pasos:

- Paso 1:
  - Descargar los archivos desde el repositorio oficial: [anventech/minich](https://github.com/anventech/minich)
- Paso 2:
  - Descargar node.js desde su página oficial: [node.js](https://nodejs.org)
  - Instalar node.js
- Paso 3:
  - Crear una carpeta para Minich (puedes ponerle el nombre que quieras)
  - Descomprimir los archivos dentro de la carpeta.
- Paso 4:
  - Abrir la línea de comandos (cmd) o la terminal de su preferencia.
  - Copiar la ruta de la carpeta creada.
  - Ejecutar el comando `cd` junto con la ruta, así: `cd <Ruta>` (sin los <>)
- Paso 5:
  - Una vez dentro de la carpeta, ejecutar el comando `npm install`, esto instalará todos los requerimientos de Minich.
  - Luego de que se instalen todos los requerimientos, dentro de la misma carpeta (en la línea de comandos), ejecutar el siguiente comando (este lo usará cada vez que quiera usar Minich): `node .`
  - Como verá al iniciar la aplicación, aparecerán varios errores, los cuales arreglaremos en el siguiente paso.
- Paso 6:
  - Una vez dentro de la aplicación, ejecutar el comando `/genConfig`, esto generará el archivo de configuración para los clientes (sin este archivo no se puede usar la aplicación)
  - Luego de ejecutar el comando `/genConfig`, veremos que en la carpeta de Minich se creó un nuevo archivo, llamado `.env`, este es el archivo de configuración para los clientes.
  - Abrimos el archivo con nuestro editor de preferencia, dentro de él estarán dos campos:
    - `DISCORD_TOKEN=`
      - En este ponemos el token de nuestro bot de Discord, quedando así: `DISCORD_TOKEN=ODc5ODg1MzcwMTE5MDQ5MzA2.YSWPGw.yfAR0xrj1SV17EmLZCLuSNmL17M`
    - `TELEGRAM_TOKEN=`
      - En este ponemos el token de nuestro bot de Telegram, quedando así: `TELEGRAM_TOKEN=1980907807:AAGf2DjFYkEUewYCuXWgGAgGxwAegvoNVi0`
  - Una vez editado, lo guardamos y volvemos a ejecutar la aplicación (si no sabes cómo, regresa al subpaso 2 del paso 5)
  - Dentro de la aplicación, ejecutamos el comando `/setup`, esto configurará la base de datos para las configuraciones de la aplicación y los contactos.
- Paso 7:
  - Luego de ese paso increíblemente largo, ya podemos usar la aplicación.

## Más información

Puedes encontrar más información sobre Minich en las siguientes páginas:

- [Funciones](/functions)

- [Comandos](/commands)
- [Clientes](/clients)