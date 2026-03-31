---

### 2. API Gateway Repository


```markdown
# Cloud-Native E-Library - API Gateway

### Student Information
* **Name:** Mahesha Dinushan Heenatigala
* **Student Number:** 2301692062
* **Slack Handle:** Mahesha Dinushan
* **GCP Project ID:** project-c341f623-6f55-4fea-bae

---

## Project Description
This repository contains the API Gateway service for the Cloud-Native E-Library platform. It acts as the single, centralized entry point for the frontend application, intelligently routing incoming HTTP requests to the appropriate backend microservices (User, Catalog, and Media). It securely manages global CORS configurations and integrates with Eureka for dynamic service discovery and load balancing.

## Technology Stack
* **Runtime:** Java 17
* **Framework:** Spring Boot 3.x
* **Cloud Tooling:** Spring Cloud Gateway, Spring Cloud LoadBalancer
* **Discovery:** Eureka Client

## Prerequisites
* Java 17 Development Kit (JDK)
* Maven (v3.8+)
* Config Server and Eureka Discovery Server must be running prior to starting this service.

## Setup & Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/MaheshaDinu/api-gateway.git
   cd api-gateway
Build the project:

Bash
mvn clean install
Run the application:

Bash
mvn spring-boot:run
The Gateway will start on port 8080 by default.
