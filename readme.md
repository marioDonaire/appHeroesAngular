# heroesApp

Aplicación hecha en Angular con el curso de [Udemy](https://www.udemy.com/course/angular-fernando-herrera/) en la cual usa los conceptos de: LazyLoads, rutas hijas, pipes, CRUD y rutas protegidas

# Comenzando 🚀

### Pre-requisitos 📋

Hay que instalar [Node.js](https://nodejs.org/es/) con [npm](https://www.npmjs.com/),[json-server](https://www.npmjs.com/package/json-server) como base de datos local y el [layout](https://www.npmjs.com/package/@angular/flex-layout) que utilizaremos.

_Para instalar Material tenemos que ejecutar el siguiente comando:_

```
ng add @angular/material
```

_Para instalar el layout que utiliza la aplicación:_

```
npm i @angular/flex-layout
```

_ y por último para instalar el servidor:_

```
npm install -g json-server
```

### Instalación 🔧

_Antes que nada necesitamos lanzar nuestro servidor, el cual si tenemos instalado json-server en el directorio donde descargemos el archivo **db.json** el comando:_

```
json-server --watch db.json
```
el cual tenemos que estar en ejecución cuando se quiera utilizar la aplicación.

_Una vez descargada la carpeta **appHeroes** tenemos que ir al directorio de esta carpeta y ejecutar el siguiente comando:_

```
npm install
```

_Y por último para lanzar el proyecto tenemos que usar el comando:_

```
ng serve -o
```

el cual una vez levantada la aplicación nos abrirá una pestaña con el proyecto ejecutado.

## Construido con 🛠️

* [Angular](https://angular.io/) 
* [npm](https://www.npmjs.com/)
* [Material](https://material.angular.io/) - componentes gráficos.
* [flex-layout](https://www.npmjs.com/package/@angular/flex-layout) - layout.
* [json-server](https://www.npmjs.com/package/json-server) - Base de datos.



## Autor ✒️

* **Mario Donaire Becerra** - *Creador* - [marioDonaire](https://github.com/marioDonaire)
* **Fernando Herrera** - *Profesor del curso* - [Kerith](https://github.com/Klerith)

## Licencia 📄

Este proyecto está bajo la Licencia CC - mira el archivo [LICENSE.md](LICENSE.md) para detalles