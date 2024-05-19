# Multi-Connector Microservices with gRPC, SOAP, GraphQL, and REST 🌐

This project demonstrates how to implement gRPC and multi-connector microservices using SOAP, REST, GraphQL, and gRPC. It covers basic gRPC communication models and integrates various web service technologies into a distributed system.

## 📘 Introduction

The project is divided into two main parts:
1. **gRPC Implementation:** Demonstrates the four basic gRPC communication models.
2. **Multi-Connector Microservices:** Builds a distributed system with customer and account services using REST, GraphQL, SOAP, and gRPC.

## 📋 Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven
- Protocol Buffers Compiler (protoc)
- Spring Boot
- gRPC Java library
- GraphQL Java library
- SOAP library (JAX-WS)

## Part 1: gRPC Implementation 🛠️

### 🔹 Unary Model

In unary RPCs, the client sends a single request and receives a single response.

### 🔹 Server Streaming Model

Server streaming RPC allows the server to send multiple responses to a single client request.

### 🔹 Client Streaming Model

Client streaming RPC lets the client send a stream of requests to the server and receive a single response.

### 🔹 Bidirectional Streaming Model

Bidirectional streaming RPC enables both the client and server to send a stream of messages to each other.

## Part 2: Multi-Connector Microservices 🌐

### 👤 Customer Service

The customer service manages customer information using:
- **REST API:** Implemented with Spring Boot.
- **GraphQL API:** Implemented with Spring Boot GraphQL.
- **SOAP API:** Implemented with JAX-WS.
- **gRPC API:** Implemented with gRPC Java.

### 💼 Account Service

The account service manages account information using:
- **REST API:** Implemented with Spring Boot.
- **GraphQL API:** Implemented with Spring Boot GraphQL.
- **SOAP API:** Implemented with JAX-WS.
- **gRPC API:** Implemented with gRPC Java.
