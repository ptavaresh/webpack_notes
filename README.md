#iniciar un npm
npm init

#Instalar dependencias disponibles en el archivo package.json devDependencies
npm install webpack --save--dev
npm install webpack-cli --save--dev

#Crear el primer bundle
node_modules\.bin\webpack src\index.js  

#Crear el bundle usando el archivo de configuracion webpack.config.js
node_modules\.bin\webpack 

#correr el servicio watch para detectar y reconpilar los cambios
npm run watch

#correr servidor local
npm run dev
