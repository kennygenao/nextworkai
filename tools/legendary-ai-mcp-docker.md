# Create a Docker Container using Cursor

**Project Link:** [View Project](http://nextwork.ai/projects/ai-mcp-docker)

**Author:** Kenny Genao  
**Email:** kgenao1@gmail.com

---

## Introducing Today's Project!

In this project, I'm going to create a Docker container using Docker MCP and Cursor.

### Key tools and concepts

The key tools I used include Cursor and Docker (desktop and mcp) Key concepts I learnt include. using an MCP enable Curosr to work across applications.

### Challenges and wins

This project took me approximately 45 minutes.

### Why I did this project

I did this project today to learn how to use a Docker MCP. Another MCP skill I want to learn is Supabase.

---

## Setting Up Cursor and Docker Desktop

In this step, I'm installing Docker Desktop. Already installed Cursor because it is an AI-powered code editor that will let us control Docker. Docker Desktop will help me run the container on our computer.

### Why Docker containers?

Docker containers package code and dependencies together so applications run identically across any computer or cloud server. They start instantly and use very little memory because they share the host system's operating system instead of bundling a whole virtual machine.

---

## Connecting Cursor to Docker with MCP

In this step, I'm enabling the Docker MCP which lets Cursor connect to Docker and manage the Docker containers.

### Installing Python and uv

To set up the Docker MCP, I ensured that I have Python and UV installed because the MCP I'll be using requires Python packages.

### What the Docker MCP can do

The Docker MCP lets me manage my Docker containers by prompting AI. The actions I can perform using Docker MCP include list containers, create containers, deploy a compose stack, get container logs.

---

## Creating My First PostgreSQL Container

In this step, I'm going to use the Docker MCP to create PostgreSQL container by prompting Cursor AI and then verify whether the container is running.

### Verifying the container

I verified my container by checking Docker Desktop where I can see the container I created using Cursor.

---

## Orchestrating Multiple Containers with Docker Compose

In this step, I'm setting up two containers, Postgre and Adminer (web UI). Docker Compose will help me create and run both of the containers at the same time.

### Setting up the docker-compose.yml file

I created a docker-compose.yml file that defines two containers. The two containers running are Postgre and Adminer - a database and web UI to see my database.

### Accessing the database in the browser

I verified my database by logging into Adminer at localhost:8080 where I can see my empty Postgre database.

---

## Monitoring Container Logs

In this project extension, I'm going to check out the logs of my containers to understand what's happening - all using AI.

### What I learned from the logs

I checked my container logs without using docker desktop or terminal by prompting cursor which use the Docker MCP tool to read and analyze the container logs

---
