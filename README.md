# MERN Stack Goal Setter Application: Dockerized and Deployed with Docker Compose  

This repository contains the implementation of a MERN (MongoDB, Express, React, Node.js) stack goal-setting application, fully containerized and deployed using **Docker Compose**. The guide includes Dockerfiles for the frontend, backend, and database services, along with a `docker-compose.yml` file to streamline deployment.

---

## Features  

- **Frontend:** React-based user interface to set and manage goals.  
- **Backend:** Node.js and Express for handling API requests and business logic.  
- **Database:** MongoDB for storing user goals securely.  
- **Dockerized Deployment:** Fully containerized setup using Dockerfiles and Docker Compose for multi-container orchestration.  

---

## Prerequisites  

Ensure you have the following installed on your system:
- [Docker](https://www.docker.com/)  
- [Docker Compose](https://docs.docker.com/compose/)  

---

Follow these steps to build and deploy the application:

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/mern-goal-setter.git
   cd mern-goal-setter
2. **Build and Start the Application**
   ```bash
   docker-compose up --build

