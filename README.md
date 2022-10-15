Docker Images
# Gives the list of images in the local system


Docker ps
# See a list of all running containers

Docker ps -a
# See a list of all containers, even the ones not runningdo


Docker rmi -f <images names>
# forcefully remove docker images


Docker login
# Login to Docker using credential


Docker prune
# Remove all unused containers, networks, images (both dangling and unreferenced)


docker build -t <username>/<appname> .
# Create image using this directory's Dockerfile
docker run -p 4000:80 friendlyname
# Run "appname" mapping port 4000 to 80
docker run -d -p 4000:80 friendlyname
# Same thing, but in detached mode


sudo docker push username/<appname>:tag
# upload tagged image to registry


Run container name mapping port 4000 to 80
# sudo docker run -d -p host port:container port container name

## docker logs


docker pull hello-seattle
## pulling images from repository


docker run -p 4000:80 friendlyname
# Run "friendlyname" mapping port 4000 to 80