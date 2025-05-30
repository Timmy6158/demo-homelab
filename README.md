# HomeLab demo
A walkthrough of how my HomeLab works

Most of the files are modifications from [Jim's Garage](https://github.com/JamesTurland/JimsGarage/blob/main/Docker-Swarm/swarm-3-nodes.sh) Check out his 
[Channel](https://www.youtube.com/@Jims-Garage)
## Hardware
2 physical machines and 1 virtual machine

## Operating System
Using Ubuntu and Linux Mint

### Why?
I am comfortable using ubuntu and its derivatives and I already had Mint installed on one of my machines. Would like to move to a server OS in the future.

## Tools

### Docker Swarm
[Doc](https://docs.docker.com/engine/swarm/) 
An excellent alternative to Kubernetes due to its simple design and configurations.

Ensures that my container are highly available(HA). This means that if one of my services go down then another machine/node can try to start up that failed 
service.

Very easy to scale up or down. Meaning that adding more machines to the Swarm will be very easy.


### 
