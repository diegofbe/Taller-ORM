# node-orm-workshop

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

1. Instalar dependencias
2. Iniciar aplicación
```sh
$ cd node-orm-workshop
$ npm install
$ npm start
```
3. Abrir postman
4. Ingresar en postman la URL proporcionada por la aplicación ( se usará http://node13.codenvy.io:46879/contacts/ como ejemplo)

### Listar
Método GET
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ y enviar la peticion

, Ejemplo: https://ibb.co/v3gff73

### Crear
Método POST
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ Ingresar en el body un texto en formato JSON con los siguientes datos
```sh
{
	"firstName": "String",
	"lastName": "String",
	"emailAddress": "String"
}
```
Y por último enviar la petición
, Ejemplo: https://ibb.co/3f6zwTn

### Editar
Método PUT
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ seguido del id del registro que se quiere editar (baseURL+/id), despues poner en el body un texto en formato JSON con los datos nuevos
```sh
{
	"firstName": "String",
	"lastName": "String",
	"emailAddress": "String"
}
```
Y por último envias la petición
, Ejemplo: https://ibb.co/51K1WwV

### Eliminar
Método DELETE
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ seguido del id del registro que se quiere eliminar (baseURL+/id) y enviar la petición
, Ejemplo: https://ibb.co/7R5Qq7h


[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
