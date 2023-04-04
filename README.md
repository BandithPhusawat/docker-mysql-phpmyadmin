# docker-mysql-phpmyadmin
docker compose mysql with phpmyadmin 

1: install docker app
2: download file docker-compose.yml
3: create folder : db_data for map volumn file database to docker container
4: start Docker App and run command : docker-compose up -d
4.1: before run command much to change you directory part in currend file docker-compose.yml
5: after run command from [4] you can check process docker container working by command : docker ps
6: after check docker process and setup env file or DatabaseConfig of Laravel project



File structure 
- Folder project
 |-- db_data
 |-- docker-compose.yml
 |-- soruce_code 
