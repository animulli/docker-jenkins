docker volume create --name jenkins_home

docker-compose up -d
or
docker-compose -p dj up --build -d

# to monitor jenkins plugin installation
docker-compose logs

docker-machine ip docker01

# to stop
docker-compose kill
