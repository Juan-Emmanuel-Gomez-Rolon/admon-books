# admon-books
Code challenge
El proyecto esta dividido en 2 partes frontend y backend
npm i
Después de correr la página
npm run dev
backend
Para ejecutar el proyecto estos son los pasos: ingresar a la carpeta de backend 
En la consola escribir lo siguiente para instalar los paquetes
npm i
Después necesitas tener en tu .env esta variable, si no la tienes debes crearla en la raíz del backend, despues copias y pegas el siguiente comando y lo guardas DATABASE_URL="file:./dev.db" Al tenerla en dicha variable se necesita correr las migraciones para eso corremos el comando
npx prisma generate dev
Y para que el servidor inicie corremos el comando
npm run dev
