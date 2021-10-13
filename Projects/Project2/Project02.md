# Project 2

## Container Technologies
- Docker
- Container platform 2

## How to install
-Docker
  -First, I updated the system 
  -Next, run sudo apt install docker and sudo apt install docker.io
  -Next, run sudo snap install docker (I use snap on my machine)
-Kubernetes (Minikube
  -First, run wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 (Most installations use snapd or wget so iused wget)
  -Next, run curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl

## Pulling a container image
- Docker
  -For docker run sudo docker pull hello-world
  -To view images on the system run docker images
- Minikube
  -I had trouble getting this one to work but first you create a deployment in minikube.
  -Next, you would use

## Running a container
- Attached and detached modes
  -
- Initializing gets the files ready to run the container and  run actually starts the container
- Run and enter shell
- To run detatched mode in docker run docker run -d hello-world
- 

## Logs & Status
- Run sudo systemctl status docker
- Reading the logs of a running container

## Stopping a container
- Pause
- Restart / resume
- Stop / kill
