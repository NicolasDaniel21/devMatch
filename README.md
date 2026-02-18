# devMatch

⚠️ Project Status: Educational / Portfolio

This repository is a personal study project. The goal is to apply backend best practices and explore the AWS ecosystem (Lambda, S3, Cognito) in a controlled environment. It is not a commercial application.

# About the Project

devMatch is a simplified freelance marketplace inspired by platforms like Upwork. It connects Clients looking for technical help with Freelancers ready to deliver solutions.

How it works:

Clients post specific technical jobs (e.g., "React Website Development").

Freelancers browse available jobs and submit tailored Proposals.

The Match: Clients review applications and select the best developer for the task.

This project serves as a backend laboratory to implement scalable patterns using NestJS and AWS Serverless architecture.


## Tech Stack & Tools

### Core Backend
* **Language:** TypeScript (Strict Mode)
* **Framework:** NestJS (Modular Architecture)
* **ORM:** Prisma
* **Database:** PostgreSQL (via Docker)

### Cloud & Infrastructure (AWS Ecosystem)
* **Compute:** AWS Lambda (Serverless approach)
* **Auth:** AWS Cognito (Identity Provider)
* **Storage:** AWS S3 (Portfolio assets & project briefs)
* **API Gateway:** Request routing and throttling

### DevOps & Quality Assurance
* **CI/CD:** GitHub Actions
* **Code Quality:** Husky & lint-staged (Pre-commit hooks)
* **Security:** GitHub CodeQL & Dependabot
* **Documentation:** Swagger (OpenAPI 3.0)
* **Testing:** Jest (Unit & Integration)

## 💻 Technical Specification

### Core Backend
* **NestJS & TypeScript:** A powerful duo providing an **opinionated architecture** and **Dependency Injection** container. This ensures a scalable, maintainable, and highly testable codebase suitable for enterprise-grade applications.
* **Prisma ORM:** Used for **end-to-end type safety**. By synchronizing the database schema with TypeScript definitions, it prevents runtime errors and ensures high developer productivity.

### Infrastructure & Cloud (AWS)
* **Serverless Architecture:** Leveraging **AWS Lambda** for cost-effective and scalable compute power.
* **Identity Management:** **AWS Cognito** handles secure user authentication and authorization (JWT-based).
* **Cloud Storage:** **AWS S3** is utilized for managing project assets and user portfolios.

### DevOps & Quality Control
* **Git Hooks (Husky & lint-staged):** Ensures that every commit adheres to project standards by running linters and formatters locally.
* **CI/CD Pipeline:** Automated workflows via **GitHub Actions** for security auditing, linting, building, and unit testing.

## 🏗 System Architecture
The project follows a decoupled approach, ensuring that business logic remains independent of external frameworks and cloud providers.
