Este es el backend para el proyecto de comercio electrónico, desarrollado con *Node.js* y *Express*.

## Tecnologías utilizadas
- *Node.js*: Entorno de ejecución para JavaScript en el backend.
- *Express*: Framework de Node.js para la creación de aplicaciones web y APIs.
- *MongoDB*: Base de datos NoSQL para almacenar datos de los productos, usuarios, órdenes, etc.
- *JWT (JSON Web Tokens)*: Para la autenticación y autorización de usuarios.

## Instrucciones para correr el proyecto

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/Victor231840/comercioElectronico2.git

   Navega al directorio del proyecto:

cd backend


3. Instala las dependencias necesarias:

npm install


4. Configura tu base de datos en el archivo .env:

MONGO_URL: URL de conexión a tu base de datos MongoDB.

JWT_SECRET: Clave secreta para la creación de JWTs.



5. Inicia el servidor:

npm start

El servidor debería estar corriendo en el puerto 5000 o el que hayas configurado.



Enlace con el Frontend

Este backend está diseñado para ser utilizado junto con el frontend del proyecto, que está disponible en el siguiente repositorio:

Frontend del Proyecto https://github.com/Victor231840/frontendComercioelectronico.git