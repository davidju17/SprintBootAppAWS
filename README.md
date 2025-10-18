&#8287;
# Spring Boot 3 AWS Deployment Examples

This repository contains a collection of Spring Boot 3 applications demonstrating different deployment strategies and configurations for AWS cloud deployment. Each project builds upon the previous one, showcasing various approaches to configuration management and cloud readiness.

## Projects Overview

### 01-hellodemo
Basic Spring Boot 3 web application with Thymeleaf template engine. Serves as a foundation demo showing core Spring Boot setup and basic web functionality.

### 02-spring-boot-3-spring-mvc-crud-local
Employee management CRUD application using Spring MVC, JPA, and MySQL database. Configured for local development environment with direct database connections.

### 03-spring-boot-3-spring-mvc-crud-aws-application-profiles
Enhanced version of the CRUD app utilizing Spring profiles for environment-specific configurations. Includes separate application properties for development and production (AWS) environments.

### 04-spring-boot-3-spring-mvc-crud-aws-environment-variables
CRUD application configured to use environment variables for database connections, making it more suitable for cloud deployment and containerization.

### 05-spring-boot-3-spring-mvc-crud-aws-environment-variables-encrypted
Advanced version with encrypted environment variables for enhanced security in AWS deployments, protecting sensitive configuration data.

### 06-bonus-spring-boot-3-spring-mvc-crud-aws-environment-variables-encrypted-with-data-refresher
Complete production-ready application featuring encrypted environment variables plus data refresh capabilities for dynamic configuration updates without application restarts.

## Getting Started

Each project contains its own Maven wrapper (`mvnw`) and can be built and run independently. Refer to individual project directories for specific setup instructions.

## Prerequisites

- Java 17
- MySQL Database
- AWS Account (for cloud deployment examples)


