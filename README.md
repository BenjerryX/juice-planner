Juice Planner
Juice Planner is a web application for creating and managing personalized juice plans, built with React, Express.js, and MongoDB Atlas, and deployed on Firebase Hosting and Render.
Prerequisites

Docker: Install Docker Desktop (https://www.docker.com/products/docker-desktop/).
Node.js: Version 18 or higher (https://nodejs.org/) for local development (optional).
MongoDB Atlas: A cloud-hosted database. Use the provided connection string or create your own (https://www.mongodb.com/atlas).
Git: To clone the repository (https://git-scm.com/).

Installation

Clone the Repository:
git clone https://github.com/BenjerryX/juice-planner.git
cd juice-planner


Verify Folder Structure:Ensure the following structure in the project root:
juice-planner/
├── docker-compose.yml
├── Juice Planner Frontend/
│   ├── juice-planner-frontend/
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   ├── src/
├── Juice Planner Backend/
│   ├── backend/  # Replace with your backend folder name
│   │   ├── Dockerfile
│   │   ├── package.json
│   │   ├── server.js


Set Environment Variables:Update docker-compose.yml with your MongoDB Atlas connection string:
environment:
  - MONGODB_URI=mongodb+srv://Benjerry:123benjerrY@cluster-benjerry.rnjjawb.mongodb.net/?retryWrites=true&w=majority&appName=cluster-Benjerry



Running the Application

Start with Docker Compose:
docker-compose up --build


Frontend: http://localhost:3000
Backend API: http://localhost:5000 (e.g., test /api/login with Postman)


Stop the Application:Press Ctrl+C and clean up:
docker-compose down



Deployment

Firebase Hosting: Front end deployed at https://juice-planner.web.app.
Render: Full application deployed at https://juice-planner-frontend.onrender.com.
Follow platform-specific guides for redeployment:
Firebase: https://firebase.google.com/docs/hosting
Render: https://render.com/docs



Repository

Source code: https://github.com/BenjerryX/juice-planner

