# Project 3

## 1: 
-For docker the available mount types are bind and volume. For a bind mount run docker -d -it --name anything --mount type=bind,source=/host,target=/targetfolder
To create a volume you want to run docker volume create volumeName. To run a container with that volume you would run docker run -d --name anything --mount source=volumeName,target=/targetfolder

-Minikube has a mount called 9P. To mount with 9P, you would run minikube mount sourceFolder:targetfolder

##2
