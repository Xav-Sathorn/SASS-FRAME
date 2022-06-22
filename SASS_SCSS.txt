create SCSS files with Live Sass Compiler

create Folders ./dist & ./SCSS
click on terminal Live Sass Compile icone

Mixin
@mixin var(){}
to call it:
@include var();

Installation:

https://openclassrooms.com/fr/courses/6106181-simplifiez-vous-le-css-avec-sass/6599386-installez-sass-sur-votre-machine#:~:text=Installation%20de%20Sass%20sur%20Windows,actuellement%20la%2014.16.1).&text=Une%20fois%20le%20t%C3%A9l%C3%A9chargement%20r%C3%A9alis%C3%A9,%E2%80%9CAdd%20to%20PATH%E2%80%9D%20coch%C3%A9s.

Installer .json
npm init
npm -g install sass

dans .jSon changer
"test": "echo \"Error: no test specified\" && exit 1"
par
"sass": "sass --watch ./sass/_main.scss:./css/style.css"

créer dossiers css + fichier style.css et sass + fichier main.scss
npm run sass