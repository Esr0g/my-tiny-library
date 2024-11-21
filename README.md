# My Tiny Library  

This is a practice project where I’ve built a Library Management System using a microservices architecture with Spring Boot. The goal is to explore how to design, develop, and manage a system composed of multiple services, each handling a specific responsibility. 

## What It Does:  

- User Management: Handle user accounts, roles, and permissions.  
- Book Management: Manage books in the library, including adding, updating, and searching.
- Loan Management: Keep track of book loans and returns.
- Notifications: Notify users about loan due dates or events.
- Authentication: Secure the system with JWT-based authentication.
- Monitoring: Set up metrics and logs to keep an eye on system performance.

## Why I Built This:  

I wanted to deepen my understanding of microservices architecture, learn how to manage inter-service communication, and explore tools like Eureka, Spring Cloud Config, and API Gateway. It’s also a great way to practice implementing best practices for distributed systems, such as monitoring, fault tolerance, and centralized configuration.  

Tech Stack:  

- Spring Boot (REST APIs, JPA, Security, etc.)
- Spring Cloud (Eureka, Config Server, API Gateway)
- PostgreSQL/MySQL for databases
- RabbitMQ/Redis/Kafka for messaging
- Docker for containerization
- Prometheus & Grafana for metrics
- ELK Stack for logging

This project is a work in progress, and I plan to keep improving it while learning more about building robust, scalable systems.  