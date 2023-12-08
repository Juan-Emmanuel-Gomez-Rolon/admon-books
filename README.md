# admon-books
Este proyecto usa Node versión 18.17.1
Frameworks y librerías: React y Express

# Como correr el proyecto
El proyecto esta dividido en 2 partes frontend y backend

### Frontend
Para correr el proyecto estos son los pasos:
ingresar a la carpeta de frontend
En la consola escribir lo siguiente para instalar los paquetes
```sh
npm i
```
Después para correr la página
```sh
npm run dev
```

### Backend
Para correr el proyecto estos son los pasos:
ingresar a la carpeta de backend
En la consola escribir lo siguiente para instalar los paquetes
```sh
npm i
```
<<<<<<< HEAD
Después necesitas tener en tu .env esta variable
DATABASE_URL="file:./dev.db"
Al tenerla en se necesita correr las migraciones para eso corremos el comando
=======
Después necesitas tener en tu .env esta variable si no la tienes debes creearla en la raíz de backend
DATABASE_URL="file:./dev.db"
Al tenerla se necesita correr las migraciones para eso corremos el comando
>>>>>>> 2a573650db73ace40b905e337d60dff60f18373a
```sh
npx prisma generate dev
```
Y para que el servidor inicie corremos el comando
```sh
npm run dev
```
