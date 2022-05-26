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