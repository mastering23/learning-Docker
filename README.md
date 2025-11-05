# 🐳 Learning Docker

This project is about learning **Docker** — a tool that helps you run apps inside **containers** so they work the same everywhere.

---

## 🚀 What is Docker?

Docker lets you package your app with everything it needs (code, libraries, system tools) and run it easily on any computer.

---

## 💡 Why Learn Docker?

- No more “it works on my machine” problems  
- Easy to set up and share apps  
- Great for testing and deployment  

---

## 🧱 Basic Commands

```bash
# Check Docker version
docker --version

# Run a test container
docker run hello-world

# See running containers
docker ps

# See all containers active | no active
docker ps -a

#Command take a image as base and create a container
docker run + imageName

#Execute container in second plane
docker run + imageName -d

#Mapped ports between containers and ports 
docker run + imageName -p

# to  assign name to specific container 
docker run + imageName --name

# to search  
docker search 

# show images 
docker images 

# download images 
docker pull + imageName 

# to removed images base on id 
docker rm + imageID

#to inspect 
docker inspect

# eliminate all containers
docker prune 


#execute command into a running container 
docker exec 

#Dockerfile is a text file that contains a set instructions used by Docker to build an image automatically

# Build an image from a Dockerfile with an assigned name (in this case, "myapp").
# The "." indicates the current directory where the Dockerfile is located.
docker build -t myapp .




```


## Create Repo  at DockerHUB | using push command 

![alt text](image.png)

![alt text](image-1.png)


## TEST 5 run a simple web page inside a Docker container using Nginx.

#### able to create a dockerfile and myapp.html build and run container @ http://localhost:7070/myapp.html

![alt text](image-2.png)

![alt text](image-3.png)

![alt text](image-4.png)