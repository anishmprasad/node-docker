```docker
docker container ls --all
docker image ls


docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)

docker rmi <image>

docker run -p 3003:3003 node-docker


To show only running containers use the given command:
docker ps

To show all containers use the given command:
docker ps -a

To show the latest created container (includes all states) use the given command:
docker ps -l

To show n last created containers (includes all states) use the given command:
docker ps -n=-1

To display total file sizes use the given command:
docker ps -s

The content presented above is from docker.com.
In the new version of Docker, commands are updated, and some management commands are added:
docker container ls

Is used to list all the running containers.
docker container ls -a

And then, if you want to clean them all,

docker rm $(docker ps -aq)
```
