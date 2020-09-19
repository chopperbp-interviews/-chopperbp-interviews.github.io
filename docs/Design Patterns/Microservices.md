---
parent: Design Patterns
layout: default
title: Microservice Architecture
nav_order: 4
---
# Microservice Architecture
[Source](https://microservices.io/patterns/index.html){:target="_blank"}

## Application architecture patterns
* Monolithic architecture
* Microservice architecture

## Decomposition
* Decompose by business capability
* Decompose by subdomain
* Self-contained Servicenew
* Service per teamnew

## Refactoring to microservicesnew
* Strangler Application
* Anti-corruption layer

## Data management
* Database per Service
* Shared database
* Saga
* API Composition
* CQRS
* Domain event
* Event sourcing

## Transactional messaging
* Transactional outbox
* Transaction log tailing
* Polling publisher

## Testing
* Service Component Test
* Consumer-driven contract test
* Consumer-side contract test

## Deployment patterns
* Multiple service instances per host
* Service instance per host
* Service instance per VM
* Service instance per Container
* Serverless deployment
* Service deployment platform

## Cross cutting concerns
* Microservice chassis
* Externalized configuration

## Communication style
* Remote Procedure Invocation
* Messaging
* Domain-specific protocol
* Idempotent Consumer

## External API
* API gateway
* Backend for front-end

## Service discovery
* Client-side discovery
* Server-side discovery
* Service registry
* Self registration
* 3rd party registration

## Reliability
* Circuit Breaker

## Security
* Access Token

## Observability
* Log aggregation
* Application metrics
* Audit logging
* Distributed tracing
* Exception tracking
* Health check API
* Log deployments and changes

## UI patterns
* Server-side page fragment composition
* Client-side UI composition