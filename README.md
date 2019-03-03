# node-orm-workshop
Primero pasos
1. Instalar dependencias (npm install)
2. Iniciar aplicación (npm start)
3. Abrir postman
4. Ingresar en postman la URL proporcionada por la aplicación ( se usará http://node13.codenvy.io:46879/contacts/ como ejemplo)

Uso de la API

# Listar
Método GET
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ y enviar la peticion
https://ibb.co/v3gff73

# Crear
Método POST
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ Ingresar en el body un texto en formato JSON con los siguientes datos
{
	"firstName": "String",
	"lastName": "String",
	"emailAddress": "String"
}
Y por último enviar la petición
https://ibb.co/3f6zwTn

# Editar
Método PUT
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ seguido del id del registro que se quiere editar (baseURL+/id), despues poner en el body un texto en formato JSON con los datos nuevos
{
	"firstName": "String",
	"lastName": "String",
	"emailAddress": "String"
}
https://ibb.co/51K1WwV
Y por último envias la petición

# Eliminar
Método DELETE
Ingresar en postman la URL http://node13.codenvy.io:46879/contacts/ seguido del id del registro que se quiere eliminar (baseURL+/id),
https://ibb.co/7R5Qq7h
Y enviar la petición
