# 🚀 SecureCart – End-to-End Azure DevOps + GitHub Copilot + DevSecOps Capstone

## 1. Capstone Overview

### Project Name

**SecureCart – Cloud-Native E-Commerce DevSecOps Platform**

### Objective

Build, secure, test, containerize, and deploy a production-style cloud-native e-commerce application on Microsoft Azure using:

* GitHub Copilot
* Visual Studio Code
* Azure DevOps
* Azure Repos
* Azure Boards
* Azure Pipelines
* Azure Container Registry
* Azure Kubernetes Service
* Kubernetes
* Helm
* Terraform
* Azure Key Vault
* Azure Monitor
* PostgreSQL
* Docker
* DevSecOps

The entire application lifecycle should be implemented with **GitHub Copilot as an AI pair programmer/engineering assistant**.

The learner starts with an almost empty local repository and progressively builds:

```text
Requirement
    ↓
Architecture
    ↓
Application
    ↓
Testing
    ↓
Docker
    ↓
Terraform
    ↓
Azure Infrastructure
    ↓
Kubernetes
    ↓
Helm
    ↓
Azure DevOps CI
    ↓
DevSecOps
    ↓
Azure Container Registry
    ↓
AKS Deployment
    ↓
Staging
    ↓
Production
    ↓
Monitoring
    ↓
Troubleshooting
    ↓
Rollback
```

---

# 2. Business Scenario

A retail company wants to build a cloud-native e-commerce platform called **SecureCart**.

Customers should be able to:

* View products
* Search products
* Filter products
* View product details
* Add products to a cart
* Checkout
* Place orders
* View order status

The organization wants the application to be:

* Cloud-native
* Containerized
* Secure
* Highly available
* Scalable
* Observable
* Automated through CI/CD
* Infrastructure-as-Code driven

The application must be deployed to **Azure Kubernetes Service (AKS)**.

---

# 3. Project Goals

The learner must demonstrate:

## Development

* Full-stack application development
* REST APIs
* Database integration
* Frontend development
* Unit testing
* Integration testing
* Error handling
* Logging

## Git

* Azure Repos
* Branching strategy
* Feature branches
* Pull requests
* Branch policies
* Code reviews

## GitHub Copilot

* Requirements analysis
* Architecture generation
* Application generation
* Code generation
* Test generation
* Refactoring
* Debugging
* Security review
* Infrastructure generation
* Pipeline generation
* Documentation

## Infrastructure

* Terraform
* Azure networking
* AKS
* ACR
* PostgreSQL
* Key Vault
* Azure Monitor

## Containers

* Docker
* Multi-stage builds
* Container security
* Azure Container Registry

## Kubernetes

* Deployments
* Services
* ConfigMaps
* Secrets
* Ingress
* HPA
* Network Policies
* Health probes
* Security contexts

## DevSecOps

* Secret scanning
* SAST
* Dependency scanning
* IaC scanning
* Container scanning
* Kubernetes security scanning

## CI/CD

* Build
* Test
* Security gates
* Container build
* Image push
* Development deployment
* Staging deployment
* Production deployment
* Approvals
* Rollback

---

# 4. Technology Stack

| Area            | Technology                      |
| --------------- | ------------------------------- |
| IDE             | Visual Studio Code              |
| AI Assistant    | GitHub Copilot                  |
| Source Control  | Azure Repos                     |
| DevOps Platform | Azure DevOps                    |
| Frontend        | React                           |
| Backend         | .NET 8 Web API                  |
| Database        | PostgreSQL                      |
| Container       | Docker                          |
| Registry        | Azure Container Registry        |
| Kubernetes      | Azure Kubernetes Service        |
| Packaging       | Helm                            |
| IaC             | Terraform                       |
| Secrets         | Azure Key Vault                 |
| Monitoring      | Azure Monitor                   |
| Logs            | Log Analytics                   |
| Secret Scan     | Gitleaks                        |
| IaC Scan        | Checkov                         |
| Container Scan  | Trivy                           |
| SAST            | Semgrep                         |
| Dependency Scan | OWASP / native package scanning |

---

# 5. Target Architecture

```text
                         ┌────────────────────────┐
                         │      Developer         │
                         │   VS Code + Copilot    │
                         └───────────┬────────────┘
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │      Azure Repos       │
                         │       Git Repository   │
                         └───────────┬────────────┘
                                     │
                                Pull Request
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │    Azure Pipelines     │
                         └───────────┬────────────┘
                                     │
                  ┌──────────────────┼──────────────────┐
                  │                  │                  │
                  ▼                  ▼                  ▼
             Unit Tests         Security          IaC Security
                                Scanning             Checkov
                  │                  │                  │
                  └──────────────────┼──────────────────┘
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │      Docker Build      │
                         └───────────┬────────────┘
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │ Azure Container        │
                         │ Registry               │
                         └───────────┬────────────┘
                                     │
                                     ▼
                         ┌────────────────────────┐
                         │          AKS           │
                         │ Azure Kubernetes       │
                         │ Service                │
                         └───────────┬────────────┘
                                     │
                     ┌───────────────┼───────────────┐
                     │               │               │
                     ▼               ▼               ▼
                 Frontend         Backend          Ingress
                                     │
                                     ▼
                                PostgreSQL
                                     │
                                     ▼
                                Key Vault

                                     │
                                     ▼
                            Azure Monitor
```

---

# 6. Environment Architecture

Create three environments:

```text
Development
    ↓
Staging
    ↓
Production
```

Recommended configuration:

| Environment | Replicas | Approval |
| ----------- | -------: | -------- |
| Development |        1 | No       |
| Staging     |        2 | Yes      |
| Production  |       3+ | Yes      |

---

# 7. Repository Structure

The final repository should look similar to:

```text
securecart/
│
├── README.md
│
├── .gitignore
│
├── docs/
│   ├── architecture.md
│   ├── deployment.md
│   ├── security.md
│   ├── troubleshooting.md
│   ├── copilot-usage.md
│   └── disaster-recovery.md
│
├── src/
│   │
│   ├── frontend/
│   │   ├── src/
│   │   │   ├── components/
│   │   │   ├── pages/
│   │   │   ├── services/
│   │   │   ├── hooks/
│   │   │   └── models/
│   │   ├── package.json
│   │   ├── Dockerfile
│   │   └── nginx.conf
│   │
│   └── backend/
│       ├── Controllers/
│       ├── Models/
│       ├── DTOs/
│       ├── Services/
│       ├── Repositories/
│       ├── Data/
│       ├── Middleware/
│       ├── Program.cs
│       ├── appsettings.json
│       ├── Dockerfile
│       └── SecureCart.Api.csproj
│
├── tests/
│   ├── backend/
│   ├── integration/
│   └── performance/
│
├── infrastructure/
│   │
│   ├── terraform/
│   │   ├── providers.tf
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   ├── outputs.tf
│   │   ├── network.tf
│   │   ├── aks.tf
│   │   ├── acr.tf
│   │   ├── postgres.tf
│   │   ├── keyvault.tf
│   │   └── monitoring.tf
│   │
│   └── scripts/
│       ├── deploy.sh
│       └── destroy.sh
│
├── kubernetes/
│   ├── namespace.yaml
│   ├── configmap.yaml
│   ├── secret.yaml
│   ├── backend-deployment.yaml
│   ├── backend-service.yaml
│   ├── frontend-deployment.yaml
│   ├── frontend-service.yaml
│   ├── ingress.yaml
│   ├── hpa.yaml
│   └── network-policy.yaml
│
├── helm/
│   └── securecart/
│       ├── Chart.yaml
│       ├── values.yaml
│       ├── values-dev.yaml
│       ├── values-stage.yaml
│       ├── values-prod.yaml
│       └── templates/
│           ├── deployment.yaml
│           ├── service.yaml
│           ├── ingress.yaml
│           ├── configmap.yaml
│           ├── hpa.yaml
│           └── networkpolicy.yaml
│
├── security/
│   ├── security-baseline.md
│   └── security-policy.yaml
│
└── pipelines/
    ├── ci.yml
    ├── security.yml
    ├── cd-dev.yml
    ├── cd-stage.yml
    └── cd-prod.yml
```

---

# 8. Prerequisites

Install:

* Visual Studio Code
* Git
* .NET 8 SDK
* Node.js LTS
* npm
* Docker Desktop
* Azure CLI
* Terraform
* kubectl
* Helm

VS Code extensions:

```text
GitHub Copilot
GitHub Copilot Chat
C#
C# Dev Kit
Docker
YAML
Terraform
Kubernetes
Azure Tools
```

Verify:

```bash
dotnet --version
node --version
npm --version
git --version
docker --version
az --version
terraform --version
kubectl version --client
helm version
```

---

# 9. Azure DevOps Project

Create an Azure DevOps project:

```text
SecureCart-DevSecOps
```

Enable:

```text
Azure Repos
Azure Boards
Azure Pipelines
Azure Artifacts
```

Create repository:

```text
securecart
```

---

# 10. Azure Boards

Create the following Epics.

## Epic 1 – Application Development

Stories:

* Create React frontend
* Create .NET API
* Product API
* Order API
* Database integration
* Product search
* Shopping cart
* Checkout
* Health checks
* Testing

## Epic 2 – Infrastructure

Stories:

* Resource Group
* Virtual Network
* Subnets
* ACR
* AKS
* PostgreSQL
* Key Vault
* Monitoring

## Epic 3 – CI/CD

Stories:

* CI pipeline
* Docker build
* ACR push
* Development deployment
* Staging deployment
* Production deployment
* Approval
* Rollback

## Epic 4 – DevSecOps

Stories:

* Secret scanning
* Dependency scanning
* SAST
* IaC scanning
* Container scanning
* Kubernetes scanning

## Epic 5 – Monitoring

Stories:

* Application logging
* Kubernetes monitoring
* Azure Monitor
* Alerts
* Troubleshooting

---

# 11. Git Branching Strategy

Use:

```text
main
 |
 +── develop
      |
      +── feature/product-api
      +── feature/order-api
      +── feature/frontend
      +── feature/terraform
      +── feature/kubernetes
      +── feature/security
```

Workflow:

```text
Feature Branch
      ↓
Pull Request
      ↓
develop
      ↓
Staging
      ↓
main
      ↓
Production
```

---

# 12. Azure Repos Branch Policies

Configure branch policies for `main`:

* Minimum 2 reviewers
* Require linked work item
* Require successful build validation
* Resolve comments
* Prevent direct pushes
* Require pull request

Configure appropriate policies for `develop`.

---

# 13. GitHub Copilot Usage Rules

GitHub Copilot should be used as an **AI pair engineer**, not as a replacement for engineering judgment.

The learner should follow:

```text
Understand
    ↓
Prompt
    ↓
Review
    ↓
Generate
    ↓
Validate
    ↓
Test
    ↓
Secure
    ↓
Deploy
```

The learner must maintain:

```text
docs/copilot-usage.md
```

Example:

```markdown
## Product API

### Requirement

Create REST APIs for products.

### Copilot Prompt

Create a ProductsController...

### Generated Files

Controllers/ProductsController.cs
DTOs/ProductDto.cs
Services/ProductService.cs

### Validation

dotnet test

### Human Review

Verified validation, error handling and database queries.
```

---

# 14. Application Development Using GitHub Copilot

## 14.1 Create Local Project

```bash
mkdir securecart
cd securecart
code .
```

---

## 14.2 Create Initial README

Create:

```text
README.md
```

Content:

```markdown
# SecureCart

SecureCart is a cloud-native e-commerce application.

## Features

- Product management
- Product search
- Shopping cart
- Checkout
- Order management
- Order tracking

## Technology

Frontend:
React

Backend:
.NET 8 Web API

Database:
PostgreSQL

Cloud:
Microsoft Azure

DevOps:
Azure DevOps

Infrastructure:
Terraform

Container:
Docker

Platform:
AKS
```

---

# 15. Copilot – Architecture Prompt

Use GitHub Copilot Chat:

```text
Read README.md.

Act as a senior full-stack and cloud architect.

Design the application architecture for SecureCart.

Technology:

- React
- .NET 8 Web API
- PostgreSQL
- Docker
- Azure Kubernetes Service
- Azure DevOps

Provide:

1. Frontend architecture
2. Backend architecture
3. Database architecture
4. API architecture
5. Configuration strategy
6. Testing strategy
7. Security considerations
8. Docker strategy

Do not generate implementation code yet.
```

Save useful output to:

```text
docs/architecture.md
```

---

# 16. Copilot – Project Structure

Prompt:

```text
Based on README.md, create a clean project structure for SecureCart.

Use:

React for frontend
.NET 8 Web API for backend
PostgreSQL for database

Create:

src/frontend
src/backend
tests
docs

Explain the purpose of each directory.
```

---

# 17. Create .NET Backend

Prompt:

```text
Create a .NET 8 Web API project under:

src/backend

Use:

- ASP.NET Core Web API
- Entity Framework Core
- PostgreSQL
- Swagger/OpenAPI
- Dependency Injection
- Configuration through environment variables

Do not hard-code secrets.

Create a clean project structure.
```

Expected:

```text
src/backend/
├── Controllers/
├── Data/
├── Models/
├── DTOs/
├── Services/
├── Repositories/
├── Middleware/
├── Program.cs
└── SecureCart.Api.csproj
```

---

# 18. Product Model

Prompt:

```text
Create a Product entity for SecureCart.

Properties:

Id
Name
Description
Category
Price
StockQuantity
ImageUrl
CreatedAt
UpdatedAt

Requirements:

- Name is required.
- Price cannot be negative.
- StockQuantity cannot be negative.
- Add appropriate validation.
- Create DTOs.
- Do not expose EF entities directly from APIs.
```

---

# 19. Order Model

Prompt:

```text
Create the Order domain model.

Order:

Id
CustomerId
OrderDate
TotalAmount
Status
Items

OrderItem:

Id
OrderId
ProductId
Quantity
UnitPrice

Statuses:

Pending
Confirmed
Shipped
Delivered
Cancelled

Configure relationships and validation.
```

---

# 20. Database Context

Prompt:

```text
Create an Entity Framework Core DbContext.

Include:

Products
Orders
OrderItems

Configure:

- Primary keys
- Foreign keys
- Relationships
- Required fields
- Decimal precision
- Useful indexes

Use PostgreSQL.

Do not store credentials in source code.
```

---

# 21. PostgreSQL Configuration

Use configuration/environment variables.

Example:

```text
ConnectionStrings__DefaultConnection
```

Do not commit real credentials.

For local development:

```text
Host=localhost;
Port=5432;
Database=securecart;
Username=securecart;
Password=<local-password>
```

---

# 22. Product API

Prompt:

```text
Create a ProductsController.

Implement:

GET /api/products
GET /api/products/{id}
POST /api/products
PUT /api/products/{id}
DELETE /api/products/{id}

Requirements:

- DTOs
- Validation
- Async operations
- Dependency injection
- Logging
- Exception handling
- Correct HTTP status codes
- No direct exposure of EF entities
```

---

# 23. Product Search

Prompt:

```text
Add product search.

Endpoint:

GET /api/products/search?query=phone

Search:

- Name
- Description
- Category

Requirements:

- Case-insensitive search
- Pagination
- Sorting
- Safe database queries
```

---

# 24. Order API

Prompt:

```text
Create OrdersController.

Implement:

POST /api/orders
GET /api/orders/{id}
GET /api/orders/customer/{customerId}
PUT /api/orders/{id}/status

Business rules:

- Order must contain at least one item.
- Product must exist.
- Quantity must be available.
- Total must be calculated by the server.
- Client must not control the final total.
- Stock must be updated safely.
- Invalid status transitions must be rejected.
- Use database transactions where required.
```

---

# 25. Health Checks

Prompt:

```text
Add ASP.NET Core health checks.

Create:

/health
/health/live
/health/ready

Make the endpoints suitable for Kubernetes liveness
and readiness probes.
```

---

# 26. Global Exception Handling

Prompt:

```text
Create global exception handling middleware.

Requirements:

- Consistent JSON error response
- Correct HTTP status codes
- No stack traces returned to clients
- Structured logging
- Correlation/request ID
- Never log secrets or credentials
```

---

# 27. Structured Logging

Prompt:

```text
Implement structured logging.

Log:

- Requests
- Request duration
- Product operations
- Order creation
- Important business events
- Errors

Do not log:

- Passwords
- Tokens
- Database credentials
- Sensitive customer data
```

---

# 28. Backend Unit Tests

Create a test project.

Prompt:

```text
Create an xUnit test project for SecureCart.

Create tests for:

- ProductService
- OrderService
- Product validation
- Order validation
- Stock validation
- Order status transitions
- Error handling

Include boundary and negative test cases.
```

Run:

```bash
dotnet test
```

---

# 29. Improve Tests with Copilot

Prompt:

```text
Review the current SecureCart tests.

Identify missing test cases for:

- Null values
- Invalid IDs
- Zero quantity
- Negative quantity
- Insufficient stock
- Empty orders
- Invalid order status
- Database failures
- Duplicate requests

Generate the missing tests.
```

---

# 30. Create React Frontend

Prompt:

```text
Create a React application under:

src/frontend

Create pages:

Home
Products
Product Details
Cart
Checkout
Orders

Use reusable components.

Create:

- Component structure
- Pages
- API service
- Hooks
- Models

Use environment-based API configuration.

Do not hard-code backend URLs.
```

---

# 31. Products Page

Prompt:

```text
Create a Products page.

Requirements:

- Retrieve products from API
- Product name
- Description
- Category
- Price
- Stock status
- Search
- Pagination
- Loading state
- Error state
- Product details navigation
```

---

# 32. Shopping Cart

Prompt:

```text
Create shopping cart functionality.

Requirements:

- Add product
- Remove product
- Change quantity
- Calculate subtotal
- Display total
- Validate available stock
- Persist cart state
- Navigate to checkout

Do not treat the client-side total as authoritative.
```

---

# 33. Checkout

Prompt:

```text
Create a checkout page.

Collect:

Customer ID
Shipping information

Display:

Products
Quantity
Price
Total

Submit the order through:

POST /api/orders

Handle:

- Success
- Validation errors
- Out-of-stock
- Server errors
- Network errors

The backend must calculate the authoritative total.
```

---

# 34. Orders Page

Prompt:

```text
Create an Orders page.

Retrieve orders for a customer.

Display:

Order ID
Order date
Items
Total
Status

Support:

Pending
Confirmed
Shipped
Delivered
Cancelled
```

---

# 35. Connect Frontend and Backend

Prompt:

```text
Review the React application and .NET API.

Create a centralized API service.

Use environment configuration for the API URL.

Handle:

400
401
403
404
500
Network errors

Do not hard-code localhost URLs inside React components.
```

---

# 36. Run Application Locally

Backend:

```bash
cd src/backend
dotnet restore
dotnet run
```

Test:

```text
GET /health
GET /api/products
```

Frontend:

```bash
cd src/frontend
npm install
npm run dev
```

---

# 37. Copilot Debugging Exercise

If something fails:

```text
The React frontend is receiving HTTP 500 when calling:

GET /api/products

Here is the browser error:

<ERROR>

Here is the backend log:

<LOG>

Analyze the problem.

Do not immediately modify code.

Explain:

1. Root cause
2. Evidence
3. Files involved
4. Validation approach
5. Recommended fix
```

Then:

```text
Implement the recommended fix.

Review the affected code for side effects.

Generate tests to prevent regression.
```

---

# 38. Application Code Review

Prompt:

```text
Review the SecureCart backend as a senior code reviewer.

Check:

- Security
- Performance
- Maintainability
- API design
- Database queries
- Validation
- Logging
- Dependency injection
- OWASP risks

Do not modify files.

Create a review report categorized as:

Critical
High
Medium
Low
```

Fix the findings.

---

# 39. Dockerization

## Backend Dockerfile

Prompt:

```text
Create a production-ready multi-stage Dockerfile for the
SecureCart .NET 8 backend.

Requirements:

- Multi-stage build
- Minimal runtime image
- Non-root user
- No secrets
- Health check
- Optimized image
```

## Frontend Dockerfile

Prompt:

```text
Create a production-ready multi-stage Dockerfile for the
SecureCart React frontend.

Use:

Node.js for build
NGINX for runtime

Requirements:

- Multi-stage build
- Minimal runtime image
- No development dependencies in final image
- Secure NGINX configuration
```

---

# 40. Build Containers

```bash
docker build -t securecart-backend ./src/backend

docker build -t securecart-frontend ./src/frontend
```

Run backend:

```bash
docker run --rm -p 8080:8080 securecart-backend
```

Run frontend:

```bash
docker run --rm -p 8081:80 securecart-frontend
```

---

# 41. Docker Security Review

Prompt:

```text
Review both Dockerfiles.

Check:

- Root user
- Excess packages
- Base image vulnerabilities
- Secrets
- Exposed ports
- Health checks
- Image size
- Layer caching
- Development dependencies

Suggest improvements.
```

---

# 42. Git Initialization

Before committing, ask Copilot:

```text
Review the repository before the first Git commit.

Identify files that should not be committed.

Look for:

- Secrets
- .env files
- Passwords
- Certificates
- node_modules
- bin
- obj
- Terraform state
- IDE files

Create an appropriate .gitignore.
```

Then:

```bash
git init
git add .
git commit -m "Initial SecureCart application"
```

---

# 43. Azure Repos Push

Create repository:

```text
securecart
```

Add remote:

```bash
git remote add origin <AZURE-REPOS-URL>
```

Push:

```bash
git branch -M main
git push -u origin main
```

Create development branch:

```bash
git checkout -b develop
git push -u origin develop
```

---

# 44. Feature Development with Copilot

Create:

```bash
git checkout -b feature/product-search
```

Prompt:

```text
Implement product category filtering across the SecureCart
application.

Requirement:

GET /api/products?category=electronics

Backend:

- API parameter
- Validation
- Database filtering
- Tests

Frontend:

- Category filter
- API integration
- Loading state
- Error handling

Documentation:

- Update API documentation

Do not break existing search functionality.

After implementation:

1. Review changes
2. Identify bugs
3. Generate tests
4. Explain validation
```

Run tests:

```bash
dotnet test
npm test
```

Commit:

```bash
git add .
git commit -m "Add product category filtering"
git push origin feature/product-search
```

Create a Pull Request in Azure Repos.

---

# 45. Copilot PR Review

Prompt:

```text
Review the product category filtering changes.

Check:

- Correctness
- Security
- Performance
- Database query efficiency
- API compatibility
- Frontend behavior
- Test coverage
- Backward compatibility

Identify issues that should be fixed before merging.
```

---

# 46. Infrastructure as Code – Terraform

Create:

```text
infrastructure/terraform
```

Copilot prompt:

```text
Act as a senior Terraform and Azure architect.

Create production-style Terraform infrastructure for SecureCart.

Resources:

- Resource Group
- Virtual Network
- Subnets
- Azure Container Registry
- AKS
- Azure PostgreSQL Flexible Server
- Azure Key Vault
- Log Analytics Workspace
- Azure Monitor

Requirements:

- Variables
- Outputs
- Managed identity
- Network separation
- Tags
- Naming conventions
- Environment support
- No secrets in Git
- Remote-state-ready design

Create:

providers.tf
variables.tf
main.tf
network.tf
aks.tf
acr.tf
postgres.tf
keyvault.tf
monitoring.tf
outputs.tf
```

---

# 47. Terraform Validation

Run:

```bash
terraform fmt -recursive
terraform init
terraform validate
terraform plan
```

Ask Copilot:

```text
Review the Terraform configuration.

Check:

- Security
- Azure resource dependencies
- Networking
- AKS security
- PostgreSQL security
- Key Vault security
- Naming
- Variables
- Outputs

Do not modify the files.

Provide a review report.
```

---

# 48. Terraform Security Scan

Install/use Checkov.

```bash
checkov -d infrastructure/terraform
```

Prompt:

```text
Analyze the Checkov findings.

For every failure:

1. Explain the security problem.
2. Explain the risk.
3. Suggest the Terraform fix.
4. Implement the fix.
5. Explain how to validate the fix.
```

---

# 49. Azure Infrastructure

Terraform should provision:

```text
Resource Group
     |
     +── Virtual Network
     |      |
     |      +── AKS subnet
     |      +── Application subnet
     |
     +── ACR
     |
     +── AKS
     |
     +── PostgreSQL
     |
     +── Key Vault
     |
     +── Log Analytics
     |
     +── Azure Monitor
```

---

# 50. Azure Container Registry

Create:

```text
securecart-backend
securecart-frontend
```

Image format:

```text
<acr-name>.azurecr.io/securecart-backend:<build-id>

<acr-name>.azurecr.io/securecart-frontend:<build-id>
```

Avoid using:

```text
latest
```

for production deployments.

Prefer:

```text
Build ID
Git SHA
Semantic version
```

---

# 51. Kubernetes

Create:

```text
kubernetes/
```

Required resources:

```text
Namespace
ConfigMap
Deployment
Service
Ingress
HPA
NetworkPolicy
```

Avoid storing production secrets directly in Git.

---

# 52. Kubernetes Copilot Prompt

```text
Create production-ready Kubernetes manifests for SecureCart.

Create:

namespace.yaml
configmap.yaml
secret.yaml
backend-deployment.yaml
backend-service.yaml
frontend-deployment.yaml
frontend-service.yaml
ingress.yaml
hpa.yaml
network-policy.yaml

Requirements:

- Separate frontend and backend
- Health probes
- Resource requests
- Resource limits
- Security context
- Non-root containers
- Read-only root filesystem where practical
- Drop unnecessary Linux capabilities
- Rolling deployment
- HPA
- Network policies
- No production secrets in Git
```

---

# 53. Kubernetes Security Review

Prompt:

```text
Review all Kubernetes manifests.

Check:

- Privileged containers
- Root user
- Linux capabilities
- Host networking
- Host filesystem access
- Resource limits
- Secrets
- Service account permissions
- Network policies
- Security context
- Read-only filesystem
- Image tags

Provide a security report and fix the findings.
```

---

# 54. Helm

Create:

```text
helm/securecart
```

Prompt:

```text
Convert the SecureCart Kubernetes manifests into a reusable
Helm chart.

Create:

Chart.yaml
values.yaml
values-dev.yaml
values-stage.yaml
values-prod.yaml

Templates:

deployment.yaml
service.yaml
ingress.yaml
configmap.yaml
hpa.yaml
networkpolicy.yaml

Requirements:

- Environment-specific configuration
- Image repository
- Image tag
- Resource configuration
- Replica count
- Environment variables
- Ingress configuration
- HPA
- Security context
- No hard-coded secrets
```

Validate:

```bash
helm lint helm/securecart
```

---

# 55. Secret Management

Never store:

```text
Database passwords
API keys
Azure credentials
Tokens
Certificates
Connection strings
```

inside source control.

Use:

```text
Azure Key Vault
+
AKS Workload Identity
```

Copilot prompt:

```text
Design a secure secret-management architecture for SecureCart.

The application runs in AKS and requires PostgreSQL credentials.

Use:

Azure Key Vault
AKS Workload Identity

Do not store secrets in:

- Git
- Dockerfiles
- Kubernetes YAML
- Helm values
- Pipeline YAML

Explain the authentication flow.
```

---

# 56. DevSecOps

Create:

```text
pipelines/security.yml
```

Security stages:

```text
Secret Scan
      ↓
Dependency Scan
      ↓
SAST
      ↓
Terraform Scan
      ↓
Docker Scan
      ↓
Kubernetes Scan
```

---

# 57. Secret Scanning

Use Gitleaks:

```bash
gitleaks detect --source .
```

Copilot prompt:

```text
Create an Azure DevOps pipeline stage using Gitleaks.

Requirements:

- Scan the repository
- Detect API keys
- Detect passwords
- Detect tokens
- Detect connection strings
- Fail the pipeline when secrets are detected
- Publish a security report
```

---

# 58. Dependency Scanning

Prompt:

```text
Add dependency vulnerability scanning.

Scan:

- .NET NuGet packages
- npm packages
- Docker dependencies

Fail the pipeline for critical vulnerabilities.

Provide an Azure DevOps implementation.
```

---

# 59. SAST

Use:

```text
Semgrep
```

Prompt:

```text
Add SAST scanning to the Azure DevOps pipeline using Semgrep.

Scan the frontend and backend.

The pipeline should:

- Run security rules
- Generate a report
- Fail on critical findings
- Make results visible in the pipeline
```

---

# 60. Container Security

Run:

```bash
trivy image <image>
```

Scan:

```text
securecart-backend
securecart-frontend
```

Recommended policy:

```text
CRITICAL → Pipeline failure
HIGH     → Warning/configurable gate
MEDIUM   → Report
LOW      → Report
```

---

# 61. Kubernetes Security Scan

Run:

```bash
trivy config kubernetes/
```

and:

```bash
trivy config helm/securecart
```

Copilot:

```text
Add Kubernetes and Helm security scanning to Azure DevOps
using Trivy.

Fail the pipeline when critical Kubernetes security
misconfigurations are detected.
```

---

# 62. Azure DevOps CI Pipeline

Create:

```text
pipelines/ci.yml
```

Pipeline:

```text
Checkout
   ↓
Build Backend
   ↓
Build Frontend
   ↓
Unit Tests
   ↓
Coverage
   ↓
Dependency Scan
   ↓
SAST
   ↓
Terraform Validate
   ↓
Checkov
   ↓
Docker Build
   ↓
Trivy
   ↓
Publish Artifacts
```

Copilot prompt:

```text
Create an Azure DevOps YAML CI pipeline for SecureCart.

The repository is Azure Repos.

Pipeline requirements:

1. Trigger on develop and main.
2. Build .NET backend.
3. Build React frontend.
4. Run unit tests.
5. Generate code coverage.
6. Run dependency scanning.
7. Run SAST.
8. Run Terraform fmt and validate.
9. Run Checkov.
10. Build backend Docker image.
11. Build frontend Docker image.
12. Run Trivy image scanning.
13. Fail for critical vulnerabilities.
14. Publish test results.
15. Publish build artifacts.

Use reusable variables.
```

---

# 63. Development Deployment

Create:

```text
pipelines/cd-dev.yml
```

Flow:

```text
Artifact
   ↓
Azure Authentication
   ↓
AKS Authentication
   ↓
Helm
   ↓
Deployment
   ↓
Rollout Check
   ↓
Smoke Test
```

Copilot:

```text
Create an Azure DevOps deployment pipeline for development.

Requirements:

- Authenticate to Azure
- Connect to AKS
- Pull images from ACR
- Deploy using Helm
- Use values-dev.yaml
- Wait for rollout
- Verify pods
- Verify services
- Run HTTP smoke test
- Fail when health checks fail
```

---

# 64. Staging Deployment

Use:

```text
values-stage.yaml
```

Add:

```text
Manual approval
```

Run:

```text
Integration tests
API tests
Smoke tests
Security validation
```

---

# 65. Production Deployment

Use:

```text
values-prod.yaml
```

Require:

```text
Production approval
```

Deployment strategy:

```text
Rolling Update
```

Advanced option:

```text
Blue/Green
Canary
```

---

# 66. Azure DevOps Environments

Create:

```text
securecart-dev
securecart-stage
securecart-prod
```

Configure:

```text
Development
Automatic

Staging
Approval

Production
Approval + branch restrictions
```

---

# 67. Complete CI/CD Flow

```text
Developer
    ↓
Feature Branch
    ↓
Azure Repos
    ↓
Pull Request
    ↓
PR Validation
    ↓
Unit Tests
    ↓
Security
    ↓
Build
    ↓
Merge
    ↓
CI
    ↓
Docker
    ↓
ACR
    ↓
Development
    ↓
Smoke Test
    ↓
Staging Approval
    ↓
Staging
    ↓
Integration Tests
    ↓
Production Approval
    ↓
Production
```

---

# 68. Pull Request Workflow

Developer:

```bash
git checkout -b feature/product-api
```

Implement using Copilot.

Then:

```bash
git add .
git commit -m "Add product API"
git push origin feature/product-api
```

Create PR:

```text
feature/product-api
        ↓
develop
```

PR pipeline must execute:

```text
Build
Tests
SAST
Dependency Scan
Secret Scan
IaC Scan
Container Scan
```

---

# 69. Monitoring

Configure:

```text
Azure Monitor
Log Analytics
Container Insights
```

Monitor:

* CPU
* Memory
* Pod restarts
* HTTP errors
* Response time
* Node health
* Application logs
* Deployment failures

Application should expose:

```text
/health
/live
/ready
```

---

# 70. Monitoring Copilot Prompt

```text
Design an observability strategy for SecureCart running on AKS.

Include:

- Application logs
- Kubernetes logs
- Container logs
- Metrics
- Health checks
- Alerts
- Azure Monitor
- Log Analytics

Suggest alerts for:

- Pod crash loops
- High CPU
- High memory
- HTTP 5xx
- High latency
- Node availability
- Failed deployments
```

---

# 71. Failure and Troubleshooting Challenge

Intentionally introduce:

```text
Kubernetes health probe failure
```

Example:

```yaml
readinessProbe:
  httpGet:
    path: /wrong-health-endpoint
    port: 8080
```

Deploy the application.

Investigate:

```bash
kubectl get pods
kubectl describe pod <pod>
kubectl logs <pod>
kubectl get events
```

Ask Copilot:

```text
The Kubernetes deployment is failing.

Here are:

kubectl describe pod
kubectl logs
kubectl get events

Analyze the problem.

Explain:

1. What failed
2. Root cause
3. Evidence
4. Correct fix
5. How to prevent this problem
```

Fix the issue and redeploy.

---

# 72. Rollback Challenge

Deploy:

```text
v1.0
```

Then:

```text
v2.0
```

Introduce a deliberate application failure.

Check:

```bash
helm history securecart
```

Rollback:

```bash
helm rollback securecart <REVISION>
```

Validate:

```bash
kubectl rollout status
```

Verify:

```text
/health
/api/products
```

---

# 73. Scaling Challenge

Generate application load.

Observe:

```bash
kubectl get hpa
```

Expected behavior:

```text
CPU increases
     ↓
HPA detects load
     ↓
Replica count increases
     ↓
Load decreases
     ↓
Pods scale down
```

Ask Copilot:

```text
Analyze the current HPA configuration.

Explain:

- Minimum replicas
- Maximum replicas
- CPU threshold
- Memory threshold
- Scaling behavior

Suggest production improvements.
```

---

# 74. Security Challenge

Ask Copilot:

```text
Perform a complete security review.

Review:

- Application
- Dockerfiles
- Terraform
- Kubernetes
- Helm
- Azure DevOps pipelines
- Dependencies
- Secrets
- Authentication
- Authorization
- Network configuration

Categorize findings:

Critical
High
Medium
Low

For every finding provide:

Finding
Risk
Evidence
Remediation
Validation
```

---

# 75. Disaster Recovery Challenge

Prompt:

```text
Design a disaster recovery strategy for SecureCart.

Consider:

- AKS failure
- PostgreSQL failure
- ACR failure
- Region failure
- Key Vault recovery
- Terraform state
- Application rollback
- Database backups
- Kubernetes configuration recovery

Provide:

RPO
RTO
Backup strategy
Recovery process
Rollback strategy
```

Save as:

```text
docs/disaster-recovery.md
```

---

# 76. Documentation

Ask Copilot:

```text
Review the entire SecureCart repository.

Generate professional technical documentation.

Include:

- Architecture
- Prerequisites
- Azure resources
- Repository structure
- Local development
- Docker
- Terraform
- AKS
- Helm
- CI/CD
- Security
- Monitoring
- Troubleshooting
- Disaster recovery
- Cleanup

Do not invent commands.

Verify commands against the actual repository.
```

Required:

```text
README.md
docs/architecture.md
docs/deployment.md
docs/security.md
docs/troubleshooting.md
docs/disaster-recovery.md
docs/copilot-usage.md
```

---

# 77. Final Repository

The completed repository should resemble:

```text
securecart/
│
├── README.md
├── .gitignore
│
├── docs/
│   ├── architecture.md
│   ├── deployment.md
│   ├── security.md
│   ├── troubleshooting.md
│   ├── disaster-recovery.md
│   └── copilot-usage.md
│
├── src/
│   ├── frontend/
│   └── backend/
│
├── tests/
│   ├── backend/
│   ├── integration/
│   └── performance/
│
├── infrastructure/
│   ├── terraform/
│   └── scripts/
│
├── kubernetes/
│
├── helm/
│   └── securecart/
│
├── security/
│
└── pipelines/
    ├── ci.yml
    ├── security.yml
    ├── cd-dev.yml
    ├── cd-stage.yml
    └── cd-prod.yml
```

---

# 78. Final End-to-End Demo

The learner must demonstrate the following scenario.

## Step 1 – Azure Boards

Create a work item:

```text
Add product category filtering
```

## Step 2 – Branch

```bash
git checkout -b feature/product-filter
```

## Step 3 – Copilot

Use Copilot to implement the feature.

## Step 4 – Test

```bash
dotnet test
npm test
```

## Step 5 – Commit

```bash
git add .
git commit -m "Add product category filtering"
git push origin feature/product-filter
```

## Step 6 – Pull Request

Create PR:

```text
feature/product-filter
        ↓
develop
```

## Step 7 – PR Security

Pipeline executes:

```text
Secret Scan
SAST
Dependency Scan
Unit Tests
Terraform Scan
```

## Step 8 – Merge

Merge after successful validation.

## Step 9 – CI

Pipeline:

```text
Build
 ↓
Test
 ↓
Security
 ↓
Docker
 ↓
Trivy
 ↓
ACR
```

## Step 10 – Development

Deploy to AKS.

## Step 11 – Staging

Approval → deployment → integration tests.

## Step 12 – Production

Approval → deployment.

## Step 13 – Monitoring

Verify:

```text
Pods
Services
Ingress
CPU
Memory
Logs
Health
```

## Step 14 – Failure

Introduce a failure.

## Step 15 – Copilot Troubleshooting

Use Copilot to analyze:

```text
Logs
Events
Pipeline output
Kubernetes status
Application errors
```

## Step 16 – Recovery

Fix or rollback.

## Step 17 – Validate

Verify:

```text
/health
/api/products
```

---

# 79. Mandatory Deliverables

The learner must submit:

```text
1. Azure DevOps Project

2. Azure Repos Repository

3. Azure Boards Work Items

4. React Application

5. .NET 8 Web API

6. PostgreSQL Integration

7. Unit Tests

8. Integration Tests

9. Dockerfiles

10. Terraform

11. Kubernetes Manifests

12. Helm Chart

13. Azure DevOps CI Pipeline

14. Azure DevOps CD Pipelines

15. Security Pipeline

16. ACR Images

17. AKS Deployment

18. Azure Key Vault Integration

19. Monitoring Configuration

20. Security Documentation

21. Architecture Diagram

22. Deployment Documentation

23. Troubleshooting Documentation

24. Disaster Recovery Documentation

25. GitHub Copilot Usage Documentation

26. Final Demo
```

---

# 80. Assessment Rubric

| Area                         |   Weight |
| ---------------------------- | -------: |
| Azure Repos & Git            |      10% |
| Application Development      |      10% |
| GitHub Copilot Usage         |      15% |
| Terraform / IaC              |      15% |
| Docker & ACR                 |      10% |
| Kubernetes / AKS             |      15% |
| CI/CD                        |      10% |
| DevSecOps                    |      10% |
| Monitoring & Troubleshooting |       5% |
| **Total**                    | **100%** |

---

# 81. GitHub Copilot Assessment

The learner should demonstrate that Copilot was used for:

* [ ] Architecture
* [ ] Project structure
* [ ] Backend
* [ ] Frontend
* [ ] Database models
* [ ] APIs
* [ ] Tests
* [ ] Dockerfiles
* [ ] Terraform
* [ ] Kubernetes
* [ ] Helm
* [ ] Azure Pipelines
* [ ] Security
* [ ] Debugging
* [ ] Documentation

---

# 82. Azure DevOps Assessment

* [ ] Azure DevOps project
* [ ] Azure Repos
* [ ] Azure Boards
* [ ] Branch strategy
* [ ] Pull requests
* [ ] Branch policies
* [ ] Build validation
* [ ] Azure Pipelines
* [ ] Environments
* [ ] Approvals
* [ ] Deployment history
* [ ] Rollback

---

# 83. Application Assessment

* [ ] React frontend
* [ ] .NET 8 API
* [ ] PostgreSQL
* [ ] Product API
* [ ] Order API
* [ ] Search
* [ ] Cart
* [ ] Checkout
* [ ] Health checks
* [ ] Logging
* [ ] Error handling
* [ ] Unit tests
* [ ] Integration tests

---

# 84. Infrastructure Assessment

* [ ] Terraform
* [ ] Resource Group
* [ ] VNet
* [ ] Subnets
* [ ] ACR
* [ ] AKS
* [ ] PostgreSQL
* [ ] Key Vault
* [ ] Log Analytics
* [ ] Azure Monitor
* [ ] Variables
* [ ] Outputs
* [ ] Validation
* [ ] Security scan

---

# 85. Kubernetes Assessment

* [ ] Namespace
* [ ] Deployments
* [ ] Services
* [ ] ConfigMaps
* [ ] Secret integration
* [ ] Ingress
* [ ] HPA
* [ ] NetworkPolicy
* [ ] Liveness probe
* [ ] Readiness probe
* [ ] Resource limits
* [ ] Security context
* [ ] Non-root container

---

# 86. DevSecOps Assessment

* [ ] Gitleaks
* [ ] SAST
* [ ] Dependency scanning
* [ ] Checkov
* [ ] Trivy
* [ ] Kubernetes scanning
* [ ] Security gates
* [ ] No secrets in Git
* [ ] Key Vault integration
* [ ] Secure container images

---

# 87. Advanced AI DevOps Challenges

## Challenge 1 – AI-Assisted Troubleshooting

Provide the learner with a failed pipeline.

They must:

```text
Analyze
   ↓
Identify root cause
   ↓
Ask Copilot
   ↓
Implement fix
   ↓
Validate
```

---

## Challenge 2 – AI-Assisted Security Remediation

Introduce:

```text
Terraform vulnerability
Docker vulnerability
Kubernetes vulnerability
Application vulnerability
```

The learner must use Copilot to:

```text
Identify
   ↓
Explain
   ↓
Fix
   ↓
Validate
```

---

## Challenge 3 – AI-Assisted Optimization

Ask Copilot to optimize:

```text
Docker image size
Terraform
Kubernetes resources
Pipeline execution time
Database queries
Application performance
```

---

## Challenge 4 – AI-Assisted Incident Response

Simulate:

```text
Application unavailable
```

The learner must investigate:

```text
Azure DevOps
    ↓
AKS
    ↓
Pods
    ↓
Services
    ↓
Ingress
    ↓
Logs
    ↓
Events
    ↓
Application
    ↓
Database
```

Then restore the application.

---

# 88. Final Golden Workflow

The learner should demonstrate:

```text
                    GitHub Copilot
                          |
                          ▼
                    Requirements
                          |
                          ▼
                    Architecture
                          |
                          ▼
                     Application
                          |
                          ▼
                       Testing
                          |
                          ▼
                       Docker
                          |
                          ▼
                      Terraform
                          |
                          ▼
                   Azure Resources
                          |
                          ▼
                     Kubernetes
                          |
                          ▼
                         Helm
                          |
                          ▼
                    Azure Pipelines
                          |
                          ▼
                     DevSecOps
                          |
                          ▼
                         ACR
                          |
                          ▼
                         AKS
                          |
                          ▼
                    Development
                          |
                          ▼
                       Staging
                          |
                          ▼
                      Production
                          |
                          ▼
                      Monitoring
                          |
                          ▼
                    Incident / Bug
                          |
                          ▼
                 Copilot Troubleshooting
                          |
                          ▼
                       Fix/Rollback
                          |
                          ▼
                     Validation
```

---

# 89. Final Success Criteria

The capstone is complete when the learner can demonstrate:

```text
Code
 ↓
Azure Repos
 ↓
Pull Request
 ↓
Code Review
 ↓
Security Validation
 ↓
Build
 ↓
Unit Tests
 ↓
Docker Build
 ↓
Container Security
 ↓
ACR
 ↓
AKS
 ↓
Helm
 ↓
Development
 ↓
Integration Tests
 ↓
Approval
 ↓
Production
 ↓
Monitoring
 ↓
Failure
 ↓
Copilot-Assisted Troubleshooting
 ↓
Rollback / Fix
 ↓
Recovery
```

The key objective is not simply to deploy an application.

The learner must demonstrate that they can use **GitHub Copilot as an AI engineering assistant throughout the complete software delivery lifecycle while applying their own engineering judgment for architecture, security, testing, infrastructure, deployment, troubleshooting, and operations.**

---

# 90. Final Capstone Statement

> **Build SecureCart from scratch using GitHub Copilot, manage the source code in Azure Repos, provision Azure infrastructure using Terraform, containerize the application with Docker, deploy it to AKS using Kubernetes and Helm, implement Azure DevOps CI/CD, enforce DevSecOps security gates, monitor the application, deliberately introduce failures, and use GitHub Copilot to troubleshoot and recover the platform.**

**Expected final outcome:**

```text
A working cloud-native application
+
Infrastructure as Code
+
Azure DevOps
+
Azure Repos
+
CI/CD
+
Kubernetes
+
AKS
+
Helm
+
DevSecOps
+
Monitoring
+
GitHub Copilot
=
End-to-End AI-Assisted DevOps Platform
```
