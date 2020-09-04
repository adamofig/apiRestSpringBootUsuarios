## Spring Boot Api example

Tutorial para crear una API de Spring boot.

Ver los vídeos para entender la construcción:

Fundamentos
https://www.youtube.com/watch?v=WVHnk04skPc&t

Rest  API 
https://www.youtube.com/watch?v=vTu2HQrXtyw

* Se actualizo el tipo de empaquetado a .jar

Rest Full Api para crear usuarios y modelos. 
 
* Get All the user
* Post a new user
* Update users
* Delete a user by id 
* Find user by properties 

### Iniciar la aplicación 
Asegurarse de tener
Java 11 + 

### Agregar la configuración de la base en applicacitons.properties 
This step is necessary

/src/main/resources/application.properties

Actualiza las siguientes propiedades 

* url 
* username 
* password

#### Ejecutalo
usar mvn para ejecutar

Windows example:

    mvnw.cmd spring-boot:run

Unix based:

    mvwn spring-boot:run 

Entrar a localhost:8080






