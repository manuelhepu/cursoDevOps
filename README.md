## Curso DevOps

# Primer Proyecto -- DockerNginxPHP

Proyecto montado en docker-compose donde tenemos las servicios de nginx y php,dentro de la carpeta src tenemos el archivo phpa mostar

# Segundo Proyecto -- DockerWordpress

Proyecto montado en docker-compose donde tenemos el servicio de wordpress, mariadb y phpmyadmin.

--phpmyadmin :
	root_password: manuel 
	localhost:8181:80

--wordpress : 
	PORT : 8080:80
	WORDPRESS_DB_HOST: rdbm
      	WORDPRESS_DB_USER: root
      	WORDPRESS_DB_PASSWORD: manuel
      	WORDPRESS_DB_NAME: exampledb

--mariadb :
	NAME : rdbm
	ROOT_PASSWORD : manuel

