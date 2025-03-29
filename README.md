# Inventory Management System

## Project Overview
The **Inventory Management System** is a scalable, microservices-based application designed to efficiently manage inventory operations. The system comprises three core services - **Product**, **Customer**, and **Transaction** - each built as independent microservices using **FastAPI**. The frontend is developed using **React** to provide a seamless and interactive user experience.

The entire application is containerized using **Docker** and deployed on **AWS ECS** for scalability. The frontend is hosted on **AWS Amplify**, and the backend leverages **AWS RDS (PostgreSQL)** for data management. API composition is achieved using **AWS Lambda**, while **API Gateway** facilitates secure API access with **Auth0-based OAuth2.0** authentication.

## Features
- **Microservices Architecture:**  
  - Independent services for **Product**, **Customer**, and **Transaction** using **FastAPI**.  
- **Scalable and Containerized:**  
  - Uses **Docker** for containerization and **AWS ECS** for deployment.  
- **Secure Authentication:**  
  - Integrates **Auth0 OAuth2.0** for secure user login.  
- **API Management:**  
  - Uses **AWS API Gateway** for secure routing and **AWS Lambda** for API composition.  
- **Frontend User Experience:**  
  - Interactive and responsive interface built with **React**, hosted on **AWS Amplify**.  
- **Data Management:**  
  - Each microservice has a separate database instance managed via **AWS RDS (PostgreSQL)**.  

## Tech Stack

### Backend:
- **FastAPI:** To build RESTful microservices.  
- **AWS ECS:** For container orchestration and service management.  
- **AWS Lambda:** To handle API composition.  
- **AWS RDS (PostgreSQL):** For database management.  
- **Docker:** To containerize the microservices.  
- **API Gateway:** To securely expose APIs.  
- **Auth0 OAuth2.0:** For secure user authentication.  

### Frontend:
- **React:** For building dynamic and interactive user interfaces.  
- **AWS Amplify:** For frontend hosting and continuous deployment.  


