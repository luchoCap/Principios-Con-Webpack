Principios con Webpack

Webpack transforma el codigo para desarrollo

Al iniciar un proyecto node se crea package

Se tiene que instalar webpack primero

Se tiene que instalar webpack-cli


npx webpack app.js -o output.js(npx es un comando que permite ejecutar cualquier modulo que tengas instalado en ese proyecto) 

cuando cree el archivo webpack.config.js ya no necesito ejecutar todo el codigo de arriba porque acá lo aclaro

npx webpack (solo eso se necesita)

npx webpack -p (este es para produccion y comprime el codigo)

npx webpack -d (este es para desarrollo y es legible el codigo)

Instalo plugins para el html y el css como por ejemplo

npm i html-webpack-plugin

webpack-dev-server es un servidor de nodejs (servidor de desarrollo, nos sirve para no estar haciendo cambios constantes en el codigo)
Por el servidor este vamos a poder reflejar los cambios automaticamente sin necesidad de refrescar la pagina

uuid es una biblioteca que te genera ids. se puede instalar con npm. y se importa como se hizo con jquery en app.js

no lo hice pero utiliza minicssextraplugin para poder ver por aparte el codigo css, sino lo ponia todo junto en el buidle.js
en la pagina del plugin dice lo que hay que hacer