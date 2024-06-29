Chat en Tiempo Real + Socket.IO y NodeJS

Que es Socket IO?

Socket.IO es una biblioteca basada en eventos para aplicaciones web en tiempo real. Permite la comunicación bidireccional en tiempo real entre clientes y servidores web. 

Que es NodeJS ?

Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto, basado en el lenguaje de programación ##JavaScript


Instalar dependencias:

 npm install

 Iniciar el servidor:

 npm start

 Siguiendo estos pasos, deberías tener tu proyecto de chat corriendo localmente con Node.js y Socket.io.

 Esto ejecutará tu archivo server.js y tu servidor debería estar corriendo en http://127.0.0.1:8000

......
Testeado en Render.com y funciona para un deploy de produccion, (para render no necesita vercel.json)

Testeado en Vercel con su archivo necesario vercel.json...

Explicacion del archivo vercel.json 

Explicación:

	1.	Version: Sigue siendo la versión 2.
	2.	Builds: Solo se define la construcción para el archivo server.js, ya que es el único archivo que necesita ser tratado específicamente con @vercel/node.
	3.	Routes: Se define una sola ruta que captura todas las solicitudes y las redirige a server.js.

 ------
