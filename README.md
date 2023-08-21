# coneccion-oracle-json

npm install
npm audit fix --force
npm install oracledb

# Instalar dotenv para usar variables de entorno

npm install dotenv

# Instalar instantClient del sistema operativo en el que estes desarrollando.

Este ejemplo es para windows 64

Instalación de Oracle Instant Client:

Descarga del Oracle Instant Client:
Ve al sitio de descargas de Oracle Instant Client: https://www.oracle.com/database/technologies/instant-client/downloads.html

Acepta los términos de uso.
Selecciona la versión de Oracle Instant Client que corresponda a tu sistema operativo (Windows 64-bit).
Descarga los archivos "Instant Client Package - Basic" y "Instant Client Package - SDK".
Extracción de los archivos:
Crea una carpeta en tu sistema donde desees instalar Oracle Instant Client. Por ejemplo, puedes crear una carpeta llamada "Oracle" en tu unidad C: (C:\Oracle).

Extrae los archivos descargados (los paquetes "Basic" y "SDK") en la carpeta que creaste.
Renombrar carpetas (opcional):
Oracle Instant Client creará una carpeta con un nombre largo. Puedes renombrar esta carpeta a algo más corto y significativo, como "instantclient".

Configuración de Variables de Entorno:

Agregar Ruta a las Bibliotecas al PATH:

Abre el menú de inicio y busca "Variables de entorno".
Selecciona "Editar las variables de entorno del sistema".
En la pestaña "Opciones avanzadas", haz clic en "Variables de entorno".
En la sección "Variables del sistema", busca la variable "Path" y haz clic en "Editar".
Haz clic en "Nuevo" y agrega la ruta a la carpeta que contiene las bibliotecas de Oracle Instant Client (por ejemplo, C:\Oracle\instantclient).
Crear la Variable ORACLE_HOME:

Haz clic en "Nuevo" en la sección "Variables del sistema".
Establece el nombre de la variable como "ORACLE_HOME".
Establece el valor de la variable como la ruta completa a la carpeta de Oracle Instant Client (por ejemplo, C:\Oracle\instantclient).
