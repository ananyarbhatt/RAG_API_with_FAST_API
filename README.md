<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Build a RAG API with FastAPI

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-devops-api)

**Author:** Ananya Bhat 22MIC0033  
**Email:** ananya.bhat2022@vitstudent.ac.in

---

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_g3h4i5j6)

---

## Introducing Today's Project!

In this project, I will demonstrate building a RAG API  I'm doing this project to learn end to end ML and Devops project

### Key services and concepts

Services I used were FAST API, UVICORN, CHROMADB, TINNYLLAMA OR OLLAMA.

### Challenges and wins

This project took me approximately two days as i came across an error, but ti was resolved as it was a network issue. The most challenging part was figuring out the error .It was most rewarding to finish a project in two days and it was so easy to follow through

### Why I did this project

I did this project because i want to know end to end execution fo MLx DEVOPS projects like tehse

---

## Setting Up Python and Ollama

In this step, I'm setting up Python and Ollama. Python is a language and Ollama is for running the LLM's locally. I need these tools because we are creating a RAG system

### Python and Ollama setup

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_i9j0k1l2)

### Verifying Python is working

### Ollama and tinyllama ready

Ollama is the AI model we will be using for the project. I downloaded the tinyllama model because tinnylama is a verison of ollamaThe model will help my RAG API 

---

## Setting Up a Python Workspace

In this step, I'm setting up a project folder called Project1 I need it because i need to activate a python venv and install dependencies

### Python workspace setup

### Virtual environment

A virtual environment is used to isntall dependencies seperates form other projects. I created one for this project to... Once I activate it... To create a virtual environment, I...

### Dependencies

The packages I installed are chromadb, fastapi for web framework, and uvicorn as the server, Ollama is used for the RAG part of the project

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_u1v2w3x4)

---

## Setting Up a Knowledge Base

In this step, I'm creating a KB. A knowledge base is liek dataabse to store your document. I need it because teh tinyllama has only been trained on some data, and we need to give specific data to gain answers


### Knowledge base setup

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_t1u2v3w4)

### Embeddings created

Embeddings are numeric version fo the text. I created them by using transformers in chromadb. The db/ folder contains chrom.sqlite with has the embeddings. This is important for RAG because it searches fr similar embedding to give you an output

---

## Building the RAG API

In this step, I'm building a RAG API.

### FastAPI setup

### How the RAG API works

My RAG API works by taking the query and converting into embeddings and comparing similar embeddings in the chroma vector db

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_f3g4h5i6)

---

## Testing the RAG API

In this step, I'm testing my RAG API.

### Testing the API

### API query breakdown

I queried my API by running the command Invoke-RestMethod -Uri "http://127.0.0.1:8000/query?q=What is Kubernetes?" -Method Post
. The command uses the POST method, which means it send the query  The API responded with Sure! Kubernezes is a comprehensive container orchestration platform that enables efficient...

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_g3h4i5j6)

### Swagger UI exploration

Swagger UI is an interactive platform. I used it to test queries by directly executing the API call/ The best part about using Swagger UI was you dont need to manually edit the code

---

## Adding Dynamic Content

In this project extension, I'm going to upgrade our RAG API

### Adding the /add endpoint

![Image](http://learn.nextwork.org/grateful_turquoise_festive_physalis/uploads/ai-devops-api_w9x0y1z2)

### Dynamic content endpoint working

The /add endpoint allows me to dynamically add knowledge base documents or information.This is useful because we can add it through swagger ui directly without having to manually chancge the code each time

---

---
