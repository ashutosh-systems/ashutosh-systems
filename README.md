# Ashutosh Sharma

Backend Engineer | Python, Django, REST APIs | Fintech Systems, Async Processing & Reliability

---

## About

Backend Engineer with 2+ years of experience building and maintaining fintech backend systems using Python, Django, Django REST Framework, and microservice-based architectures.

Worked on onboarding, loan processing, identity, notification, reconciliation, workflow automation, and document management systems involving multiple services, background processing, and external integrations.

Experience includes backend API development, bank and third-party integrations, workflow execution systems, async processing, query optimization, production debugging, and improving system reliability under real production conditions.

Worked on client-specific fintech workflows for Tyger Capital (formerly Adani Capital), including onboarding flows, reconciliation-related workflows, bank integrations, document management features, and live production support.

Also contributed to a DAG-based workflow application for Kinara Capital Private Limited, where workflows progressed through different stages based on validations, user actions, and background task execution.

Focuses on building backend systems that are predictable, traceable, and maintainable while handling retries, failures, delayed execution, and inconsistent external dependencies.

---

## Core Strengths

Backend APIs • Distributed Workflows • Async Processing  
Production Debugging • Query Optimization • Reliability  
Failure Handling • Idempotency • Data Consistency  
Celery • RabbitMQ • Redis • PostgreSQL  

---

## Work

### Fintech Backend Systems

- Built and maintained backend APIs using Django and Django REST Framework
- Worked on onboarding, loan processing, identity, notification, reconciliation, and document-related modules
- Handled multi-service workflows involving validations, background tasks, and external integrations
- Worked on client-specific backend workflows and production support requirements

### Workflow Systems

- Worked on multi-step workflow systems where execution depended on previous states and validations
- Managed dependencies between workflow stages and background processing
- Handled retries, failures, delayed execution, and inconsistent states across services
- Contributed to DAG-based workflow execution systems for configurable business processes

### Document Management System

- Built APIs for secure document upload, retrieval, and sharing
- Worked on document storage and retrieval workflows across cloud storage systems
- Implemented token-based document access and controlled retrieval flows
- Reduced unnecessary database operations and improved retrieval performance

### Background Processing

- Implemented async/background jobs using Celery, RabbitMQ, and Redis
- Used background processing for notifications, integrations, delayed tasks, and workflow execution
- Handled queue backlogs, retried tasks, delayed execution, and failure recovery
- Moved heavy or unreliable operations outside the request-response cycle

### External Integrations

- Worked on bank API and third-party service integrations
- Handled failures, retries, timeouts, and inconsistent responses from external systems
- Improved stability during partial execution and dependency failures
- Debugged integration issues through request tracing and production logs

---

## Core Work

- Designing and maintaining backend APIs and workflow systems
- Building APIs for onboarding, loan processing, identity, notification, and reconciliation flows
- Managing multi-step execution flows and workflow state transitions
- Implementing async/background processing using Celery and RabbitMQ
- Debugging production issues across API → queue → worker → database layers
- Fixing slow APIs caused by inefficient queries and repeated database calls
- Optimizing queries using indexing, pagination, select_related, and prefetch_related
- Improving backend reliability through root-cause fixes and execution flow improvements
- Handling failures in external APIs and distributed service interactions
- Supporting deployments and production systems using Docker and AWS ECS

---

## Engineering

- Keep APIs lightweight and avoid blocking operations
- Move heavy or unreliable work outside request flow
- Design tasks carefully to avoid duplicate execution
- Make system behavior explicit and traceable
- Optimize queries before scaling infrastructure
- Use caching only where it improves actual performance
- Prefer simpler systems for easier debugging and maintenance
- Focus on predictable execution under real production conditions

---

## Production

- Investigated delayed and stuck Celery task execution
- Fixed slow endpoints caused by inefficient database access
- Improved reliability by addressing root causes instead of temporary fixes
- Handled failures and inconsistent responses from external dependencies
- Reduced latency by restructuring backend execution flow
- Debugged issues using logs, task tracing, and request flow analysis
- Worked on live production support for fintech backend systems
- Improved deployment consistency using Docker, CI/CD, and AWS services

---

## Stack

### Languages
Python, SQL

### Backend
Django, Django REST Framework, FastAPI, Flask

### Messaging & Background Jobs
Celery, RabbitMQ, Redis

### Databases
PostgreSQL, MySQL, MongoDB, DynamoDB

### Cloud & Infrastructure
AWS ECS, S3, CloudWatch, Route53

### DevOps & Tooling
Docker, Git, GitHub Actions, CI/CD  
Logging, Monitoring, Debugging Tools

### APIs & Security
REST APIs, OAuth2, SAML  
Bank API Integrations, Third-Party Integrations

### AI-Assisted Development
Claude Code

---

## Focus

Build backend systems that behave predictably under real-world conditions

Improve reliability through debugging, query optimization, and cleaner execution flow

Handle retries, failures, background processing, and distributed workflows carefully

Keep systems maintainable, traceable, and simpler to operate in production

---

## Contact

LinkedIn: https://www.linkedin.com/in/ashushm/  
Email: ashushm8795@gmail.com
