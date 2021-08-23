cd webapp/target
copy webapp.war G:\Programming\docker\udemy
docker build -t customimage G:\Programming\docker\udemy
docker run -d -p 8888:8080 --name rubai customimage
