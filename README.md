# Diseño Responsive para administración de proyectos

Es una sencilla estructura para un proyecto web estático

## Modo de uso

1. Cree un fork de este repositorio y clonelo en local (o descargue este repositorio por zip).
2. Ejecute en terminal `npm install -g gulp-cli`
3. Ejecute `npm install` (asegurese de tener npm actualizado y Nodejs en v6 como minimo)
4. Ejecute `gulp dev` para trabajar e desarrollo
5. Ejecute `gulp build` para compilar sus archivos para produccion

## Estructura

1. La carpeta **src** contiene la estructura de archivos con la que trabajará
2. La carpeta **public** contiene los archivos compilados que deberan llevarse a producción
3. Para Sass importe sus partials desde `styles.scss`, el orden está indicado en el mismo archivo
4. Para Pug, la carpeta `pages` contiene las paginas del proyecto y la carpeta `includes` los bloques.
5. Para Js, la carpeta `modules` contiene los módulos que serán importados desde `index.js`

Plantilla Usada 
* [EDboilerplate](https://github.com/escueladigital/EDboilerplate)
EDboilerplate es gratis, open source y de la comunidad para la comunidad.

### Screenshot ⌨️

![alt text](https://raw.githubusercontent.com/edw-rys/design-project-management/master/docs/assets/img/cap.png)
![alt text](https://raw.githubusercontent.com/edw-rys/design-project-management/master/docs/assets/img/cap-mb.png)
