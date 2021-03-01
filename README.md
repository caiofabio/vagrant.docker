# Atividade Vagrant Files + Informações.
imagem utilizada "ubuntu/bionic64".
configurado para MySQL-Server 5.7.
user:vagrant passw:root


# Atividade DockerMySQL.

docker run -p 3306:3306 -e MYSQL_ALLOW_EMPTY_PASSWORD=yes mysql:5.6
