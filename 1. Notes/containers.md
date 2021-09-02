### ##########################
### Site Reliability Engineering [Container_Notes]
### ##########################


### Keywords
- SDDC (Software Defined Data Center)
      - Server Virtualization (Hypervisors)
      - Storage Virtualization (SAN)
      - Network Virtualization (SDN)


### Container Runtimes
- Docker
- CRI-O
- Rkt
- Containerd
- Podman


### Container Orchestration Engines (COE)
- Kubernetes
- Apache Meso
- Docker Swarm
- EKS
- ECS
- AKS
- GKE

### Docker Architecture
- Docker host
- Docker Daemon
- Docker client
- Docker images
- Docker containers
- Docker registry (Within a registry there will be multiple repositories)
      - Public (hub.docker.com) --> GitHub for your images
      - Private (AWS ECR)


### Analogy for Docker

Dockerfile ~= Vagrantfile ~= CloudFormation ~= Terraform ~= Vrealize templates
Docker images ~= Vagrant Box ~= Amazon AMI ~= VMware Templates
Docker containers ~= Virtual Machines ~= Amazon EC2 ~= VMware VMs


### Class Activity
````
1. Install docker
2. create a user docker-admin (make sure to use command "adduser" and not "useradd")
3. usermod -aG docker docker-admin (Run this command as root)
4. Search image for nginx using docker search or by going to hub.docker.com
5. Pull the image to your docker host
6. Run a container from this newly pulled image

````


### Docker commands
````
docker search keyword
docker images (docker image ls) --> List all images on Docker host
docker pull nginx --> pull nginx image from Docker hub to you local Docker host
docker ps (docker container ls) --> List all running containers
docker ps -a (docker container ls -a) --> List all running/stopped containers
docker run -it <imagename>

-i - interactive
-t - terminal/tty
-d - detached / daemonized



````




### References
- https://docs.docker.com/get-started/overview/
- https://get.docker.com/
- https://hub.docker.com/
- 



