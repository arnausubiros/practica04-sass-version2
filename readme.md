# Practica04 - Sass

## Instalación de Sass con Bootstrap 5

- requisitos Node.js
- extensiones de Visual Studio Code : Open Live Server y Live Sass Compiler

- en el area de trabajo abrimos el terminal :

  ##### - npm init -y

  ##### - npm install bootstrap

- Añadimos la carpeta js de /node_modules/boostrap/dist/js
  (solo nos interesab los archivo bootstrap.min.js y bootstrap.min.map)
- Creamos el archivo .gitignore para que no se incluyan ciertos archivos y carpetas : /node_modules , /sass y .gitignore
  -.,,

- añadimos una fuente de Google Fonts (https://fonts.google.com/ ) - copiaremos el codigo con @import en el archivo custom.scss
- revisar el archivo \_variables.scsss localizado en /node_modules/bootstrap/scss/\_variables.scss
  $font-family-base: 'Cormorant Garamond', serif; cursive;
