# Eureka Discovery Server

## Overview

This is a **Spring Boot Eureka Discovery Server** used for service registration and discovery
in the microservices architecture.

- **Purpose:** Allow microservices to register themselves and discover other services.
- **Not user-facing:** Only microservices interact with it.
- **No business logic:** Only acts as a registry.

---

## Configuration

Application properties:

```yaml
server:
  port: 8761

eureka:
  client:
    registerWithEureka: false
    fetchRegistry: false
