# CMS Microservices - Adding a New Service

Welcome to the CMS Microservices project! This guide will walk you through the process of adding a new service to the project, ensuring consistency and proper integration with the existing architecture.

## Project Structure

```plaintext
cms-microservices/
│
├── services/
│   ├── user-service/
│   ├── file-service/
│   ├── content-service/
│   ├── notification-service/
│   ├── search-service/
│   ├── analytics-service/
│   └── <your-new-service>/
│
└── docs/
    └── design/
```

## Pre-requisites
Before you start, make sure you have the following:

- Java 17 installed.
- Maven installed and configured.
- Familiarity with Spring Boot and Apache Camel.
- Understanding of the project's architecture and existing services.

## Step-By-Step Guide

1. Navigate to the `services` folder
2. Create your project from [microservices-template](https://github.com/Digitalchain-IT/microservice-template)
