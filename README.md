# 🚀 Service Registry – Spring Boot Eureka Server

This project is a **Service Registry (Eureka Server)** built using Spring Boot and Spring Cloud.  
It acts as a **central discovery service** in a microservices architecture — enabling other services (like API services, gateways, and more) to **register themselves and discover each other dynamically**.

---

## 🔎 Overview

In a distributed microservices system, services must locate and communicate with each other efficiently.  
A **Service Registry** is a core component that:

- Keeps track of all running service instances
- Supports dynamic discovery
- Helps avoid hard-coded service URLs

This project implements a **Netflix Eureka Server** as a Service Registry. :contentReference[oaicite:1]{index=1}

---

## 🛠 Tech Stack

| Component | Technology |
|-----------|------------|
| Language | Java |
| Framework | Spring Boot |
| Service Registry | Spring Cloud Netflix Eureka |
| Build Tool | Maven |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

src/
├─ main/
│ ├─ java/
│ │ └─ (Eureka Server Code)
│ └─ resources/
│ └─ application.yml
pom.xml
