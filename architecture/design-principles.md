# Architecture and Design Principles Prompt

When designing the architecture, ensure it follows these principles:

## Core Principles

1. **Separation of Concerns**:
   - Divide functionality into distinct sections
   - Each section addresses a separate concern
   - Minimize overlap between concerns

2. **Modularity**:
   - Design loosely coupled, highly cohesive modules
   - Each module should have a single, well-defined purpose
   - Modules should be independently deployable and testable

3. **Scalability**:
   - Design for horizontal and vertical scaling
   - Consider performance under load
   - Plan for growth in users, data, and features

4. **Maintainability**:
   - Write code that is easy to understand and modify
   - Use consistent patterns and conventions
   - Minimize technical debt

5. **Reliability**:
   - Design for failure tolerance
   - Implement proper error handling and recovery
   - Include monitoring and alerting

6. **Security**:
   - Security by design, not as an afterthought
   - Follow principle of least privilege
   - Validate all inputs and outputs

## Architecture Patterns

Consider these patterns where appropriate:
- Layered Architecture
- Microservices
- Event-Driven Architecture
- Domain-Driven Design
- CQRS (Command Query Responsibility Segregation)
- Repository Pattern
- Factory Pattern
- Dependency Injection

## Key Questions

Before finalizing design, answer:
- How will this scale?
- What are the failure modes?
- How will we monitor and debug?
- What are the security implications?
- How does this integrate with existing systems?

## Usage

Use this prompt when planning system architecture or making significant design decisions.
