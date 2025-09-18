

Usuario Paa login
jlopez
JL2025*

node src/tests/db.test.js
npx jest tests/usuario.test.js


Instrucciones para levantar el proyecto

 Iniciar el servidor en Plesk

Ingresar a Plesk
Accede al panel de Plesk de tu servidor.

Crear un sitio para Node.js

Ve a Sitios web y dominios → Añadir dominio/subdominio (o usa uno existente).

Selecciona Configuración de Node.js para ese dominio.

Subir tu proyecto

Puedes subir tu proyecto a través de FTP, Git o Plesk Git.

Si usas Git, en Plesk:

Ve a Git → Clonar repositorio → pega https://github.com/juancanchila/rcd_back.git.

Instalar dependencias

En Configuración de Node.js, hay un botón que dice NPM Install.

Haz clic para instalar todas las dependencias (npm install).

Configurar variables de entorno

En Configuración de Node.js → Variables de entorno, agrega:

PORT=3002
JWT_SECRET=clave_super_secreta_epa
COOKIE_NAME=token_epa
DB_NAME=epacartagena
DB_USER=root
DB_PASSWORD=1q2w3e4r5tPD!!
DB_HOST=localhost


Seleccionar el archivo de inicio

En Configuración de Node.js, indica el archivo de arranque del proyecto, normalmente app.js o server.js (dependiendo de tu proyecto).

Iniciar la aplicación

Haz clic en Aplicar y luego en Iniciar aplicación.

Tu proyecto debería estar corriendo en la URL del dominio/subdominio configurado.