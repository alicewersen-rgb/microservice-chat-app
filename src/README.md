# Distributed Chat App

A distributed chat application built as a microservices-based system.

## Technologies

- Java 21
- Spring Boot
- Spring Security
- JWT Authentication
- gRPC
- RabbitMQ
- H2 Database
- Maven

## Services

- BFF (Backend for Frontend)
- Auth Service
- User Service
- Message Service

## Architecture

Client
↓
BFF (REST)
↓
Auth Service
User Service
Message Service
↓
RabbitMQ

Message Service communicates with User Service using gRPC.