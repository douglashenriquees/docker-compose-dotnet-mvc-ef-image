## Docker Compose

* ```dotnet publish -c Release -o dist```
* ```docker-compose build```
* ```docker-compose up -d```
* ```docker container ps -a```
* ```docker container exec -it docker-compose-dotnet-mvc-ef-image_mysql_1 /bin/bash```
* ```mysql -u root -p```
* ```show databases;```
* ```docker-compose down -v --rmi all```
  * ```--rmi all``` remove também as imagens que foram baixadas para o **host**