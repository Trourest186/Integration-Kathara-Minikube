# Hybrid-Kathara-Minikube

![image](https://github.com/Trourest186/Hybrid-Kathara-Minikube/assets/74035725/6a65a3b5-1a68-4085-9bae-db4a3bf4fb3c)

## Prerequisites
- Prepare a Kathara machine [References](https://github.com/Trourest186/Kathara/blob/main/README.md)
- Setup for remoting Docker Daemon
  - Use "kathara settings" for inserting URL
  - Add "Configuring remote access with systemd unit file" 

    [Original 1](https://docs.docker.com/config/daemon/remote-access/)
    [Original 2](https://docs.docker.com/engine/reference/commandline/dockerd/#daemon-socket-option)
    [Stackoverflows](https://stackoverflow.com/questions/56130644/connecting-to-a-remote-docker-daemon)
  
- At the computers managed by kathara
  ```
  export DOCKER_HOST="tcp://(IP_HOST):2375"
  ```

## Install Minikube
- [Mikube](https://r2schools.com/how-to-install-minikube-on-ubuntu-22-04-lts/)
- [Original](https://www.youtube.com/watch?v=qG7FGVWijeM&t=200s)

## Using with tutorial documents
- [References](https://minikube.sigs.k8s.io/docs/)

## Lab
- [Links](https://github.com/Trourest186/Kathara/tree/main/Lab_networks)

## Other References
- [Docker in Docker](https://hub.docker.com/_/docker/)
- [Kind](https://github.com/kubernetes-sigs/kind)
