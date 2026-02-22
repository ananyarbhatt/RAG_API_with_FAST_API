<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Containerize a RAG API with Docker

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-devops-docker)

**Author:** Ananya Bhat 22MIC0033  
**Email:** ananya.bhat2022@vitstudent.ac.in

---

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_x7y8z9a0)

---

## Introducing Today's Project!

In this project, I will demonstrate how to containerize the RAG api i have built priorly. I'm doing this project to learn containerisation and orchestration as well as key concepts fo ML and DevOps

### Key services and concepts

Services I used were docker. concepts I learnt include containerization to integrate the rag into a ci cd pipeline

### Challenges and wins

This project took me approximately two days due to errors in between. The most challenging part was troubleshooting the error.It was most rewarding to make the applicaitona ccessible by creating containers

### Why I did this project

I did this project because i wanted to elarn abut devops in ai further

---

## Setting Up the RAG API

In this step, I'm setting up im going to Set up your RAG API's code, database and dependencies,Set up your virtual environment,Run Ollama 

### API setup and workspace

In this step, I will Set up a virtual environment,Install all dependencies,Run embed.py to build the database,
Make sure everything matches your setup

### Dependencies installed

The packages I installed are as above image 

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_c9d0e1f2)

### Local API working

I tested that my API works by running the command and posting the question.The local API responded with the json response above in the image. This confirms that ollama is running and we are getting accurate outputs.

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_v5w6x7y8)

---

## Installing Docker Desktop

### Docker Desktop setup

Docker Desktop is an application for containerizing an application. Containerization will help my project by alloweing this application to run on any system without dependency problems.

### Docker verification

I verifies if docker is running with the hello world image.

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_i9j0k1l2)

---

## Creating the Dockerfile

Now we create the dockerfile, docker iamge and test it


### How the Dockerfile works

A Dockerfile is is a set of instructions that tells Docker how to build your container image. Think of it as a recipe - each line adds a layer to your image.

### Containerized API test results

Testing the API after containerization proved that the docker iamge is running. 

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_o1p2q3r4)

---

## Building and Running the Container

### Docker image build complete

 I verified my Docker image was built successfully by docker images | Select-String rag-app.
This confirms that my API is now containerized because it shows the altest image running is that of the rag api.

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_p9q0r1s2)

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_x7y8z9a0)

---

## Pushing to Docker Hub

Create a Docker Hub account

Tag your image for Docker Hub

Push your image to Docker Hub

Pull and run your image from Docker Hub

### Docker Hub push complete

I pushed to Docker Hub by the push command, after tagging the docker container

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_m5n6o7p8)

### Pulling from Docker Hub

Pulling an image from Docker Hub means anyone can pull the docker image and use it. When I ran docker pull, Docker it pulled the docker image from the docker hub and displayed it. The difference between building locally and pulling from Docker Hub is anyone can acces it from anywhere.

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-docker_f5g6h7i8)

---

---
