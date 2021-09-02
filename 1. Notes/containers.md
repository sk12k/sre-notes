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


### Activity
````
1. Install docker 
2. create a user docker-admin (make sure to use command "adduser" and not "useradd")
3. usermod -aG docker docker-admin (Run this command as root)
4. 
````


### Docker commands
````
docker images (docker image ls)
docker ps (docker container ls)


````




### References
- https://docs.docker.com/get-started/overview/
- https://get.docker.com/
- https://hub.docker.com/
- 



