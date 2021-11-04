# Project 3

## 1: 
-For docker the available mount types are bind and volume. For a bind mount run docker -d -it --name anything --mount type=bind,source=/host,target=/targetfolder
To create a volume you want to run docker volume create volumeName. To run a container with that volume you would run docker run -d --name anything --mount source=volumeName,target=/targetfolder

-Minikube has a mount called 9P. To mount with 9P, you would run minikube mount sourceFolder:targetfolder

## 2
-In docker to build an image, you need to run: docker build (with a PATH or url). In order to create a dockerfile you will need to add the lines: 

FROM "any base image"

COPY "this will copy files from a source and place them in the a destination provided by the user"

RUN "a command that will run with the dockerfile"

These will be used in  most dockerfiles and are the bases for writing dockerfiles.

-Even though it is possible to build image with minikubes, the steps to do so use docker image buildingto create the image so I went with buildah to complete the second part of 2.

-adfasd
