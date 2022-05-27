# Entorno de trabajo Angular 13

```
ng --version
ng new app
```

## Instalar boostrap 5, jquery and popper
```
npm install bootstrap jquery @popperjs/core
```
### En angular.json
```
"build":
"styles": [
  "node_modules/bootstrap/dist/css/bootstrap.min.css",
  "src/styles.scss"
],
"scripts": [
  "node_modules/jquery/dist/jquery.min.js",
  "node_modules/@popperjs/core/dist/umd/popper.min.js",
  "node_modules/bootstrap/dist/js/bootstrap.min.js"
]
```

## Install json-server
```
npm install -g json-server
```

## Install Order, Search and Pagination
```
npm i ng2-search-filter
npm i ng2-order-pipe
npm i ngx-pagination
```
### Luego, importar clases en el modulo
```
Ng2SearchPipeModule
Ng2OrderModule
NgxPaginationModule
```

## Install Fontawesome
```
ng add @fortawesome/angular-fontawesome
```
### Luego, importar en app.module
```
import { FontAwesomeModule } from '@fortawesome/angular-fontawesome';
```
### Luego, importar en *.component.ts
```
import { faCoffee } from '@fortawesome/free-solid-svg-icons';

export class AppComponent {
  faCoffee = faCoffee;
}
```
### Luego, agregar en *.component.html
```
<fa-icon [icon]="faCoffee"></fa-icon>
```


