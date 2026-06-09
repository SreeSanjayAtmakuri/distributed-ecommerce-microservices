# E-Commerce Microservices Architecture

## Overview

This project follows a microservices architecture where each business capability is developed as an independent service.

## Planned Services

### API Gateway

Acts as the single entry point for all client requests.

### Order Service

Handles order creation, validation, and management.

### Inventory Service

Manages product stock and availability.

### Payment Service

Processes payment transactions and payment status updates.

### Notification Service

Handles email and notification delivery to users.

## Communication Flow

Client → API Gateway → Services

Services communicate using Apache Kafka events.

## Databases

* PostgreSQL for transactional data
* MongoDB for product catalog data

## Future Integrations

* Spring Security
* JWT Authentication
* Docker
* Kubernetes
* Monitoring and Logging
