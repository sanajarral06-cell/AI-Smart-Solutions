# AI Smart Solutions

## Project Title
AI Smart Solutions

## Final Year Project

This repository contains the development work, source code, documentation, and resources for our Final Year Project.

## Group Members and Roles

- Sana Mehmood — Team Leader / Software Developer
- Esha Shahzad — AI/ML Developer
- Manahil Naeem — UI/UX Designer / Developer
- Laiba Jamil SAP ID: 55132, BS SE -7
-Manahil Waseem (54035)
 
**Project Description**
A Flask web application integrated with Redis using Docker and Docker Compose.

## CI/CD Pipeline
GitHub Actions is used to automate:
- Docker image building
- Application testing
- Pushing images to Docker Hub
- Application deployment

The workflow runs when code is pushed to the main branch.

## Technologies
- GitHub
- GitHub Actions
- Docker
- Docker Compose
- Docker Hub
- Flask
- Redis
- AWS EC2

## How to Run
1. Clone the repository.
2. Run the application using:

```bash
docker compose up -d
```

3. Check containers:

```bash
docker ps
```

4. Open: `http://localhost:8035/`

## Docker Hub

Image: `40283/mid-app:54035`

## Changelog

- Updated README documentation.
- Added GitHub Actions workflow.
- Automated Docker image build and push.
- Added deployment automation
