# VOS-service

An architectural diagram for a Video Online Streaming (VOS) service, with similar features as Netflix and Amazon Prime Video.

## Architecture

A microservices architecture implementing CQRS is used to reduce complexity between services.

## Functional diagram

Core components to enable a functioning system, without consideration for scalability and performance.

## Non-functional diagram

Performance is improved using a CDN to reduce latency between client and resource. Scalability is improved through provisioning multiple instances for services and placing load balancers for high traffic services.
