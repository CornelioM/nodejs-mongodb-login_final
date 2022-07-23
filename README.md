# Notes App Nodejs-Mongodb-VersionFinal

Esta es una aplicación básica para administrar notas simples en la web utilizando tecnologías Javascript como Nodejs, Mongodb y otras tecnologías relacionadas.

Esta aplicación puede hacer:

- Operaciones CRUD: crear/leer/actualizar/borrar notas
- Permite a un usuario iniciar sesión y guardar sus notas personales

### Installation

```sh
npm i
sudo service mongod start # ejecutar el servicio mongodb
npm run dev # ejecutar en modo de desarrollo
npm start # ejecutar en modo de producción
```

> Necesitas establecer un MONGODB_URI variable de entorno para conectarse a Mongodb

### Environment Variables

Esta aplicación necesita las siguientes variables de entorno

- `MONGODB_URI` esta es la cadena URI de Mongodb
- `PORT` el puerto http del servidor para la aplicación
- `NODE_ENV` entorno de node


### Default User

cuando se inicia la aplicación, se creará un usuario administrador con las siguientes credenciales:

- email: admin@localhost
- password: adminpassword

