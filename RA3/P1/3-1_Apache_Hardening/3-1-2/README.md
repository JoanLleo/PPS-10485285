Para realizar este ejercicio, nos podemos bajar la imagen directamente de dockerhub sobre la que vamos a trabajar

	docker pull pps10485285/ra3:3-1-1

Podemos descargarnos la imagen ya finalizada 

	INSERTAR ENLACE

O ejecutar los siguientes comandos para construirla desde el Dockerfile facilitado:


Creamos una imagen de Docker a partir del Dockerfile 

	docker build -t apache:p2 .

Creamos el contenedor y lo ejecutamos 

	docker run -d --name apache-P2 -p 4443:443 apache:p2

Accedemos a nuestro Container desde el navegador:

	https://localhost:4443

