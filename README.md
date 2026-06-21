# Create a Docker Container using Cursor

**Project Link:** [View Project](http://learn.nextwork.org/projects/ai-mcp-docker)

**Author:** Akshay Ajgaonkar  
**Email:** ajgaonkarakshay@gmail.com

---

---

## Introducing Today's Project!

In this project, I'm going to use cursor to create docker containers and help manage them

### Key tools and concepts

The key tools I used include docker and cursor to setup postgresql database and adminer. Key concepts I learnt include how to use cursor to easily manage infrastructure as code using natural language making it really easy and fun to work with.

### Challenges and wins

This project took me approximately 30 mins/ The most challenging part was cursor free tier limit reaching.

### Why I did this project

I did this project today to learn how to use docker with cursor. Another MCP skill I want to learn is workflow automation with Github mcp, CI/CD automation, live querying data mcp etc.

---

## Setting Up Cursor and Docker Desktop

In this step, I'm installing Cursor and Docker Desktop/ I need Cursor because it will help me write code for Desktop. Docker Desktop will help me orchestrate and run docker containers for this project.

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_8h9i0j1k)

### Why Docker containers?

Docker containers are useful because they help create a lightweight environment with all dependencies to run an application.

---

## Connecting Cursor to Docker with MCP

In this step, I'm enabling the Docker MCP which lets Cursor manage and control docker containers and real infrastructure  from Cursor's chat.

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_8g9h0i1j)

### Installing Python and uv

To set up the Docker MCP, I installed Python and UV because I wanted to build project in python and wanted a package manger to install dependencies

### What the Docker MCP can do

The Docker MCP lets me deploy-stack. The actions I can perform using Docker MCP include Removing/stopping containers
Inspecting images or volumes
Building images
Managing networks
docker exec into containers

---

## Creating My First PostgreSQL Container

In this step, I'm going to use the Docker MCP to create a PostgreSQL container using the Docker MCP. And then Verify the container is running in Docker Desktop.

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_7k8m9n0p)

### Verifying the container

I verified my container by checking Docker Desktop where I can see that my container my-db is running.

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_2q3r4s5t)

---

## Orchestrating Multiple Containers with Docker Compose

In this step, I'm setting up a project folder on my Desktop. Docker Compose will help me set up PostgreSQL and Adminer so that I can connect and query my to PostgreSQL database.

### Setting up the docker-compose.yml file

I created a docker-compose.yml file that defines postgresql database and Adminer web interface. The two containers running are my-db: The PostgreSQL database container where the data actually lives and adminer: The web interface container that acts as a visual window, letting us log in and view our database directly using the browser.

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_x7z1b4c6)

### Accessing the database in the browser

I verified my database by logging into Adminer at localhost:8080 where I can see a login screen. I added the following details.
System: 
Server: 
Username:
Password:
Database:

---

## Monitoring Container Logs

In this project extension, I'm going to use the Docker MCP to check my container's logs and understand what the log entries mean

![Image](http://learn.nextwork.org/calm_amber_swift_tayberry/uploads/ai-mcp-docker_9y0z1a2b)

### What I learned from the logs

I checked my container logs using cursor but I reached my free tier limit so I had to use the terminal to get logs and take a look at them.

---

---
