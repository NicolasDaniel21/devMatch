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

## 🏗 System Architecture
The project follows a decoupled approach, ensuring that business logic remains independent of external frameworks and cloud providers.
