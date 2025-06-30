# Juice Planner Application

## Overview
Juice Planner is a web application designed to help users create and manage personalized juice plans. Built with a modern tech stack, it features a responsive React front end, an Express.js backend, and a MongoDB Atlas database, with containerization using Docker and deployments on Firebase Hosting and Render.

## Features
Create and manage juice plans with user-friendly interfaces
Secure user authentication using JSON Web Tokens (JWT)
Responsive design with Tailwind CSS for seamless use across devices
Cloud-hosted MongoDB Atlas for persistent data storage
Dockerized front end and back end for consistent development and deployment
Deployed on Firebase Hosting (front end) and Render (full stack)
Version control with Git and semantic versioning

## Project Structure
docker-compose.yml: Orchestrates Docker services for front end and back end
Juice Planner Frontend/juice-planner-frontend/:
Dockerfile: Docker configuration for the React front end
package.json: Front-end dependencies (React, Tailwind CSS, Craco)
src/: React components and source code
Juice Planner Backend/backend/:
Dockerfile: Docker configuration for the Express.js back end
package.json: Back-end dependencies (Express.js, JWT, MongoDB)
server.js: Main server file for API endpoints


README.md: Project documentation and installation instructions

## Getting Started

### Requirements
Docker: Docker Desktop (https://www.docker.com/products/docker-desktop/)
Node.js: Version 18 or higher (https://nodejs.org/) for local development (optional)
MongoDB Atlas: Cloud-hosted database (https://www.mongodb.com/atlas)
Git: For cloning the repository (https://git-scm.com/)

### Installation
Clone the repository:git clone https://github.com/BenjerryX/juice-planner.git
cd juice-planner

### Docker
Update docker-compose.yml with the correct MongoDB Atlas connection string and backend folder path:environment:
  - MONGODB_URI=mongodb+srv://Benjerry:123benjerrY@cluster-benjerry.rnjjawb.mongodb.net/?retryWrites=true&w=majority&appName=cluster-Benjerry



## Running the Application

Start with Docker Compose:docker-compose up --build
Frontend: http://localhost:3000
Backend API: http://localhost:5000 (e.g., test /api/login with Postman)
Stop the application:docker-compose down



## Deployment
Firebase Hosting: Front end at https://juice-planner.web.app
Render: Full stack at https://juice-planner-frontend.onrender.com
Redeployment guides:
Firebase: https://firebase.google.com/docs/hosting
Render: https://render.com/docs



## Repository

Source code: https://github.com/BenjerryX/juice-planner
