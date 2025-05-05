✅ Sprint 1 Goals Recap (In order of execution):
Priority	Task	Notes
🔵 1	Implement User entity and repository	Use Lombok + JPA
🔵 2	Build Register and Login endpoints	With Spring Security + JWT
🔵 3	Add JWT token filter + security config	Protect routes
🔵 4	Write unit tests for AuthService using TDD	With JUnit + Mockito
🔵 5	Document AuthController with Swagger annotations	OpenAPI docs
🔵 6	Add Checkstyle and fix code style issues	Use google_checks.xml
🔵 7	Generate Jacoco coverage report	Target: 80%+




🚀 Sprint 1 – Project Setup & Authentication (Epic 1 + 9)
[EPIC 1] Setup Spring Boot project with auth-service module

Configure PostgreSQL

Setup application.properties

Setup folder structure

[EPIC 1] Implement User entity and JPA repository

[EPIC 1] Implement Register and Login endpoints using Spring Security and JWT

[EPIC 1] Secure endpoints using JWT token filter

[EPIC 9] Add Swagger/OpenAPI documentation for AuthController

[EPIC 9] Write unit tests for AuthService using TDD approach

[EPIC 9] Add Checkstyle with Google rules and fix all lint errors

[EPIC 9] Configure Jacoco and generate test coverage report

🧾 Sprint 2 – Expense Management (Epic 2)
[EPIC 2] Create Expense entity with fields: title, amount, date, category, receipt (file)

[EPIC 2] Implement endpoints: create, get all, get by ID, delete expense

[EPIC 2] Implement file upload logic for receipts (PDF/Image)

[EPIC 2] Write unit + integration tests for ExpenseService

[EPIC 9] Document all ExpenseController endpoints using Swagger

👨‍💼 Sprint 3 – Approval Workflow (Epic 3 + 6)
[EPIC 3] Create Manager view for pending expenses

[EPIC 3] Implement approve/reject endpoints with comments

[EPIC 6] Add mock email notification on approval/rejection (console log for now)

[EPIC 9] Add integration tests for approval workflow

⚙️ Sprint 4 – Admin and RBAC (Epic 4)
[EPIC 4] Admin can view and edit users and roles

[EPIC 4] Implement endpoint to assign role to a user

[EPIC 4] Enforce role-based access at method level using @PreAuthorize

📈 Sprint 5 – Reporting & Analytics (Epic 5)
[EPIC 5] Implement monthly expense summary by category

[EPIC 5] Add export-to-PDF support using iText

[EPIC 9] Write test cases for reporting logic

🐳 Sprint 6 – DevOps & CI/CD (Epic 7)
[EPIC 7] Write Dockerfile and docker-compose for local setup (auth + Postgres)

[EPIC 7] Setup GitHub Actions for CI: test + lint + jacoco

[EPIC 7] Optional: Configure Jenkins pipeline for CI/CD

📊 Sprint 7 – Observability (Epic 8)
[EPIC 8] Add Spring Boot Actuator endpoints

[EPIC 8] Add Prometheus + Grafana integration

[EPIC 8] Monitor health, metrics, and JVM info

✅ Sprint 8 – Final Testing and Deployment
[EPIC 9] Write end-to-end tests using Testcontainers

[EPIC 9] Ensure test coverage > 85% using Jacoco

[EPIC 9] Clean up Swagger docs, validate all APIs

[EPIC 7] Push final Docker image to registry (Docker Hub or GCP)