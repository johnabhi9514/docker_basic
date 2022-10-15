Docker Images
# Gives the list of images in the local system
![images](https://user-images.githubusercontent.com/62017340/195981460-f83909ae-ed9a-4212-a044-1bb568e78c22.png)


Docker ps
# See a list of all running containers
![images1](https://user-images.githubusercontent.com/62017340/195981471-3a0cbb04-f85c-488e-8c9e-924309c7aeb2.png)

Docker ps -a
# See a list of all containers, even the ones not runningdo


Docker rmi -f <images names>
# forcefully remove docker images


Docker login
# Login to Docker using credential
 ![images2](https://user-images.githubusercontent.com/62017340/195982332-ef729674-fa10-40f9-9814-6ced78779a4c.png)

 
 
Docker prune
# Remove all unused containers, networks, images (both dangling and unreferenced)
![images4](https://user-images.githubusercontent.com/62017340/195981502-a38f1275-8090-47a7-b75f-15c0c8832a07.png)
 

docker build -t <username>/<appname> .
# Create image using this directory's Dockerfile
docker run -p 4000:80 friendlyname
# Run "appname" mapping port 4000 to 80
docker run -d -p 4000:80 friendlyname
# Same thing, but in detached mode

![images5](https://user-images.githubusercontent.com/62017340/195982548-3aa5cd24-39ed-4fe4-841d-82fe29133290.png)


![images7](https://user-images.githubusercontent.com/62017340/195982493-a3e4972b-6200-4a0e-b048-adbf90e801c8.png)


 
sudo docker push username/<appname>:tag
# upload tagged image to registry
 file:///home/abh/Desktop/Industrial_Project/Docker/Hello%20World/images/images6.png
Run container name mapping port 4000 to 80
# sudo docker run -d -p host port:container port container name

![images7](https://user-images.githubusercontent.com/62017340/195981536-97bb8ee3-982e-46a3-b897-032cd26bc558.png)

## docker logs


docker pull hello-seattle
## pulling images from repository
![images8](https://user-images.githubusercontent.com/62017340/195982437-e283b549-f15b-4151-8e09-6a0e792acdac.png)


docker run -p 4000:80 friendlyname
# Run "friendlyname" mapping port 4000 to 80

Docker Image to Docker hub.
![images12](https://user-images.githubusercontent.com/62017340/195983277-d9773b70-16b5-4037-b05d-d4c3e3fc03d1.png)

