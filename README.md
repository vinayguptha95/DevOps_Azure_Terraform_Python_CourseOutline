# DevOps_Azure_Terraform_Python_CourseOutline

Github links for this Training

1. <a href=https://github.com/kmitsolution/Python> Python </a>

##### Week 1 ( 4 days Python 1 day git) 
##### Week 2 (1 day Git and Github,4 days Azure Fundamentals & Entraid)
##### Week 3 ( 2 days networking,3 Terraform, )
##### Week 4 ( 2 days docker, 2 days kubernetes,1 Github Actions)
##### Week 5 ( 1 day Github Actions, 4 days Castone project)

# <img width="30" height="33" alt="image" src="https://github.com/user-attachments/assets/61a14b24-1532-4739-80d9-2f39e3a71b8d" />
 **Python (Basic To Advance) )**

<details>
<summary>📘 <strong>Python Module(Week1 3 days)</strong></summary>

---

### 🧩 **Module 1: Python Basics **

<details>
<summary><strong>1.1 Variables and Data Types</strong></summary>

**Topics:**

* Variable declaration and naming rules
* Primitive data types: `int`, `float`, `str`, `bool`, `complex`
* Type checking with `type()` and `isinstance()`
* Mutable vs Immutable types
* Dynamic typing in Python

**Assignments:**

1. Create a program that takes user input for name, age, and height, and prints a formatted introduction.
2. Write a script that swaps two variables without using a third variable.
3. Demonstrate mutable and immutable behavior using `list` and `tuple`.

</details>

<details>
<summary><strong>1.2 Conditions and Iterations</strong></summary>

**Topics:**

* Conditional statements: `if`, `elif`, `else`
* Loops: `for`, `while`
* Loop control statements: `break`, `continue`, `pass`
* Nested loops and conditionals
* Comprehensions: list, dict, set

**Assignments:**

1. Write a program to check if a number is prime.
2. Print all even numbers between 1 and 100.
3. Create a multiplication table generator using nested loops.
4. Generate squares of even numbers using list comprehension.

</details>

<details>
<summary><strong>1.3 Type Casting and Exceptions</strong></summary>

**Topics:**

* Implicit and explicit type casting
* Common casting functions (`int()`, `float()`, `str()`, `list()`, etc.)
* Exception handling using `try`, `except`, `else`, `finally`
* Custom exceptions using `raise`
* Multiple exception handling

**Assignments:**

1. Write a calculator that performs division and handles `ZeroDivisionError`.
2. Create a function that takes input from user and handles invalid integer input.
3. Define a custom exception for invalid age input (e.g., negative numbers).

</details>

<details>
<summary><strong>1.4 Functions and Built-in Functions</strong></summary>

**Topics:**

* Defining and calling functions
* Function arguments: positional, keyword, default, variable-length (`*args`, `**kwargs`)
* Return values
* Scope and lifetime of variables
* Common built-in functions (`map`, `filter`, `zip`, `enumerate`, `sorted`, etc.)
* Lambda functions

**Assignments:**

1. Write a function that checks whether a number is palindrome.
2. Implement a function using `map()` to convert a list of strings to uppercase.
3. Create a lambda function to sort a list of tuples based on the second element.

</details>

<details>
<summary><strong>1.5 Data Structures</strong></summary>

**Topics:**

* Lists, Tuples, Sets, Dictionaries
* Operations: insertion, deletion, slicing, membership
* Iterating through collections
* Nested data structures
* Difference between shallow and deep copies (`copy` module)

**Assignments:**

1. Write a program to count frequency of words in a sentence using a dictionary.
2. Implement a program that removes duplicates from a list using a set.
3. Sort a dictionary by its values.

</details>

---

###  **Module 2: Object-Oriented Programming (OOPs)**

<details>
<summary><strong>2.1 Introduction to OOPs</strong></summary>

**Topics:**

* Procedural vs Object-Oriented Programming
* Benefits of OOPs
* Classes and Objects in Python
* Syntax of class creation and object instantiation

**Assignments:**

1. Create a simple `Car` class with attributes `brand`, `model`, and a method `start()`.
2. Compare the procedural and OOP approach to compute student grades.

</details>

<details>
<summary><strong>2.2 Core OOPs Concepts</strong></summary>

**Topics:**

* Encapsulation
* Inheritance
* Polymorphism
* Data Abstraction

**Assignments:**

1. Implement inheritance using a `Vehicle` superclass and `Car`/`Bike` subclasses.
2. Demonstrate polymorphism using a method with the same name in different classes.
3. Create a class with private attributes and public getter/setter methods.

</details>

<details>
<summary><strong>2.3 Class Attributes and Instance Attributes</strong></summary>

**Topics:**

* Class vs Instance attributes
* Accessing attributes using `self`
* Modifying attributes at instance and class level

**Assignments:**

1. Create a class `Employee` with a class variable `company_name` and instance variables for `name`, `salary`.
2. Demonstrate how changing class variables affects all objects.

</details>

<details>
<summary><strong>2.4 Class Methods and Instance Methods</strong></summary>

**Topics:**

* Defining instance methods
* Class methods using `@classmethod`
* Static methods using `@staticmethod`
* When to use each method type

**Assignments:**

1. Create a `Student` class with:

   * Instance method: `display_info()`
   * Class method: `from_string(cls, student_str)`
   * Static method: `is_passing(score)`

</details>

<details>
<summary><strong>2.5 Initialization and Access Modifiers</strong></summary>

**Topics:**

* `__init__()` constructor
* Private and protected attributes (`_`, `__`)
* Naming conventions for access control

**Assignments:**

1. Implement a `BankAccount` class that initializes with `account_number`, `balance`, and supports deposit/withdraw.
2. Make balance a private attribute and access it using methods.

</details>

<details>
<summary><strong>2.6 Properties (Getters and Setters)</strong></summary>

**Topics:**

* Using `@property` and `@<attribute>.setter`
* Data validation using properties
* Difference between property and traditional getter/setter methods

**Assignments:**

1. Create a `Temperature` class with a `celsius` attribute and a derived `fahrenheit` property.
2. Implement data validation to ensure temperature doesn’t go below absolute zero.

</details>

---

### ⚙️ **Module 3: Advanced OOPs and Design Principles**

<details>
<summary><strong>3.1 Advanced Classes and Inheritance</strong></summary>

**Topics:**

* Multiple inheritance
* Method Resolution Order (MRO)
* `super()` function
* Composition vs Inheritance

**Assignments:**

1. Demonstrate multiple inheritance with two parent classes (`Bird`, `FlyingObject`).
2. Implement a `super()` call chain in a multi-level inheritance scenario.

</details>

<details>
<summary><strong>3.2 SOLID Principles</strong></summary>

**Topics:**

* S – Single Responsibility
* O – Open/Closed
* L – Liskov Substitution
* I – Interface Segregation
* D – Dependency Inversion

**Assignments:**

1. Refactor a given class violating SRP.
2. Implement an example demonstrating OCP and DIP.

</details>

<details>
<summary><strong>3.3 Object-Oriented Paradigms</strong></summary>

**Topics:**

* Class-based vs prototype-based languages
* Understanding of TDD (Test Driven Development)
* BDD (Behavior Driven Development)
* DDD (Domain Driven Design)

**Assignments:**

1. Write unit tests for your `BankAccount` class using `unittest`.
2. Describe how DDD could structure a “Library Management System”.

</details>

<details>
<summary><strong>3.4 Protocols and Networking Concepts</strong></summary>

**Topics:**

* Introduction to HTTPS, gRPC, and TCP
* Understanding request-response cycle
* Serialization and deserialization concepts

**Assignments:**

1. Create a Python script using `requests` to call a public API.
2. Implement a simple TCP client-server using `socket`.

</details>

<details>
<summary><strong>3.5 Content Negotiation</strong></summary>

**Topics:**

* Request/Response headers
* MIME types
* JSON/XML negotiation
* RESTful API data exchange

**Assignments:**

1. Build a small Python Application to call REST API

</details>

</details>

</details>

---

---

 **Git & GitHub Administration**

<details>
<summary> <strong>Git & GitHub Administration Module</strong></summary>

---

##  **Module 1: Git**

<details>
<summary><strong>1.1 Introduction to Git and Version Control</strong></summary>

**Topics:**

* Introduction to version control systems (Centralized vs Distributed)
* Benefits of version control in software development
* Introduction to Git and how it works
* Basic Git workflow overview (local and remote repositories)

**Assignments:**

1. Explain the difference between centralized and distributed version control with examples.
2. Set up a local Git repository and connect it to GitHub.
3. Demonstrate the full Git workflow (init → add → commit → push → pull).

</details>

---

<details>
<summary><strong>1.2 Core Git Commands</strong></summary>

**Topics:**

* `git init`, `git clone`, `git status`, `git add`, `git commit`
* Branch management: `git branch`, `git checkout`, `git merge`
* Viewing logs and history
* Working with `.gitignore` files

**Assignments:**

1. Create a local repository and practice basic Git commands.
2. Create multiple branches and merge them with proper commit history.
3. Demonstrate how `.gitignore` helps in excluding unnecessary files.

</details>

---

<details>
<summary><strong>1.3 Collaboration with Git Platforms</strong></summary>

**Topics:**

* Collaborating using GitHub
* Forking and cloning repositories
* Creating pull requests (or merge requests)
* Resolving merge conflicts

**Assignments:**

1. Fork a public repository and create a pull request.
2. Collaborate with a teammate using branches and pull requests.
3. Practice resolving merge conflicts in a shared repository.

</details>

---

<details>
<summary><strong>1.4 Best Practices in Git & DevOps</strong></summary>

**Topics:**

* Writing effective commit messages
* Understanding Gitflow branching model
* Code review and PR best practices
* Maintaining repository hygiene

**Assignments:**

1. Create a GitFlow-based workflow for a sample project.
2. Perform a code review on a pull request and suggest improvements.
3. Draft commit message guidelines for your team.

</details>



---

##  **Module 2: GitHub Administration**

<details>
<summary><strong>2.1 Introduction To Github Administration</strong></summary>

**Topics:**

* Introduction to DevOps and why it’s needed
* Benefits of DevOps principles
* GitHub vs GitHub Enterprise overview
* Organizations, Teams, and Repositories
* Understanding GitHub roles and permission levels
* Managing users and access

**Assignments:**

1. Create a GitHub organization with multiple repositories.
2. Assign roles and permissions for different team members.
3. Document differences between GitHub and GitHub Enterprise.

</details>

---

<details>
<summary><strong>2.2 Repository and Access Management</strong></summary>

**Topics:**

* SSO and identity federation (GitHub Enterprise)
* Repository management (public vs private)
* Branching rules and protection


**Assignments:**

1. Configure protected branches and approval workflows.

</details>

---

<details>
<summary><strong>2.4 Using IDEs with Git (VS Code)</strong></summary>

**Topics:**

* Using IDEs (e.g., VS Code, Visual Studio Code)
* Downloading and installing VS Code
* Getting familiar with the VS Code interface
* Setting up a new project and connecting to Git
* Basic features: themes, customization, extensions
* Integrated terminal and file management
* Debugging in VS Code
* IntelliSense and snippets
* Remote development and language/framework setup

**Assignments:**

1. Install VS Code and configure Git integration.
2. Clone a repository and manage it from within VS Code.
3. Debug a Python or JavaScript project using VS Code.

</details>

---
</details>

### Containerization 

<details>
<summary> <strong>Module: Containerization – Basic and Intermediate</strong></summary>

---

##  **Section 1: Introduction to Containerization & Docker Basics**

<details>
<summary><strong>1.1 Understanding Containerization</strong></summary>

**Topics:**

* What is Containerization?
* Differences between Virtual Machines and Containers
* Introduction to Docker
* Key concepts: Images, Containers, Docker Engine, Docker Hub

**Assignments:**

1. Define containerization and compare it with virtualization.
2. Create a short report on how Docker revolutionized application deployment.
3. Install Docker Desktop on your local machine and verify setup.

</details>

---

<details>
<summary><strong>1.2 Setting Up Docker</strong></summary>

**Topics:**

* Installing Docker on Windows, Mac, and Linux
* Docker CLI vs Docker Desktop Overview
* Running your first Docker container
* Docker Images vs Containers explained

**Assignments:**

1. Install Docker and run container.
2. List all running containers using Docker CLI.
3. Compare Docker CLI and Docker Desktop interfaces.

</details>

---

<details>
<summary><strong>1.3 Working with Docker Images</strong></summary>

**Topics:**

* Understanding Dockerfile and how images are built
* Common Docker commands: `docker run`, `docker ps`, `docker stop`, `docker rm`
* Working with Docker Hub (pulling and pushing images)
* Writing Dockerfiles from scratch to advance level (MultiStage Dockerfile)
* Understanding layers and caching in Docker images

**Assignments:**

1. Create a Dockerfile for a simple Python or Node.js app .
2. Build and push your custom image to Docker Hub.
3. Inspect image layers using `docker history`.

</details>

---

<details>
<summary><strong>1.4 Dockerfile and Image Best Practices</strong></summary>

**Topics:**

* Best practices for Dockerfile writing
* Using `docker build` and tagging images
* Image versioning and naming conventions

**Assignments:**

1. Rewrite a Dockerfile using multi-stage builds.
2. Optimize a Dockerfile to reduce image size.
3. Tag and push multiple versions of an image to Docker Hub.

</details>

---

## **Section 2: Docker Storage and Networking**

<details>
<summary><strong>2.1 Volumes and Storage</strong></summary>

**Topics:**

* Docker Volumes 
* Introduction to Docker storage: Volumes vs Bind mounts
* Creating and managing volumes

**Assignments:**

1. Create named and anonymous volumes and inspect them.
2. Mount a host directory as a bind mount into a container.
3. Explain differences between volumes and bind mounts.

</details>

---

<details>
<summary><strong>2.2 Networking in Docker</strong></summary>

**Topics:**

* Basic Docker networking concepts
* Bridge,host,none network
* Using Docker network commands

**Assignments:**

1. Create a custom Docker network and connect multiple containers.
2. Expose ports and test container accessibility.
3. Demonstrate inter-container communication using bridge network.

</details>

---

##  **Section 3: Docker Compose and Advanced Concepts**

<details>
<summary><strong>3.1 Docker Compose Basics</strong></summary>

**Topics:**

* Introduction to Docker Compose
* Writing a simple `docker-compose.yml` file
* Managing multi-container applications with Docker Compose
* Scaling services and using environment variables in Compose

**Assignments:**

1. Write a `docker-compose.yml` for a two-service app (e.g., web + database).
2. Scale containers horizontally using Compose.
3. Demonstrate the use of environment variables in Compose files.

</details>

---

<details>
<summary><strong>3.2 Docker Optimization and Monitoring</strong></summary>

**Topics:**

* Docker image optimization techniques
* Container logging and monitoring basics
* Debugging running containers

**Assignments:**

1. Optimize an existing Docker image using build caching and minimal base images.
2. Use `docker logs` and `docker stats` for container monitoring.
3. Practice debugging a misconfigured container.

</details>

---


</details>

### **Kubernetes (K8s) **

<details>
<summary> <strong>Module: Kubernetes (K8s) – Basics (Beginner)</strong></summary>

---

##  **Section 1: Introduction to Container Orchestration**

<details>
<summary><strong>1.1 Overview of Container Orchestration</strong></summary>

**Topics:**

* What is container orchestration?
* Why orchestration is needed in containerized environments
* Comparison between Docker Swarm and Kubernetes
* Role of Kubernetes in managing containers at scale

**Assignments:**

1. Write a short summary comparing Docker Compose and Kubernetes.
2. Explain the purpose of container orchestration with real-world examples.
3. Identify use cases where Kubernetes is beneficial.

</details>

---

## ⚙️ **Section 2: Kubernetes Architecture**

<details>
<summary><strong>2.1 Understanding Kubernetes Components</strong></summary>

**Topics:**

* Basic Kubernetes architecture overview
* Control Plane (Master) components:

  * API Server
  * etcd
  * Controller Manager
  * Scheduler
* Worker Node components:

  * Kubelet
  * Kube Proxy
  * Container Runtime

**Assignments:**

1. Create a labeled diagram of the Kubernetes architecture.
2. Explain the role of each major Kubernetes component.
3. Describe how pods are scheduled and managed within the cluster.

</details>

---

##  **Section 3: Kubernetes Key Concepts**

<details>
<summary><strong>3.1 Core Kubernetes Objects</strong></summary>

**Topics:**

* Cluster and Node overview
* Pods: smallest deployable units
* Deployments and ReplicaSets (basic intro)
* Services and Networking basics (ClusterIP, NodePort, LoadBalancer)

**Assignments:**

1. Deploy your first Pod using `kubectl run`.
2. Create a simple Deployment and expose it using a Service.
3. Explain how Services enable communication between Pods.

</details>

---

## 🧭 **Section 4: Helm and Kubernetes Security**

<details>
<summary><strong>4.1 Helm Charts and Kubernetes Security Basics</strong></summary>

**Topics:**

* Introduction to Helm: package manager for Kubernetes
* Understanding Charts, Templates, and Releases
* Installing and managing applications using Helm
* Basic Kubernetes security concepts:

  * Namespaces and Role-Based Access Control (RBAC)
  * Secrets and ConfigMaps

**Assignments:**

1. Install Helm on your system and deploy a sample Helm chart.
2. Create and deploy a simple custom Helm chart.
3. Create and manage a Kubernetes Secret and ConfigMap.

</details>

---

</details>

---
###  **GitHub Actions – CI/CD Pipeline using Git, Docker, and Kubernetes**

<details>
<summary> <strong>Module: GitHub Actions CI/CD – Automating Build, Test, and Deployment</strong></summary>

---

##  **Section 1: Pipeline Design and Setup**

<details>
<summary><strong>1.1 Pipeline Overview</strong></summary>

**Topics:**

* End-to-end workflow: Code → Build → Test → Deploy
* Understanding GitHub Actions components: Events, Jobs, Steps, Runners
* Folder structure for CI/CD pipelines (`.github/workflows/`)
* Using repository secrets for credentials and kubeconfig

**Assignments:**

1. Design a pipeline diagram showing integration from Git → Docker → Kubernetes.
2. Create a new repository and configure GitHub Secrets (`DOCKER_USERNAME`, `DOCKER_PASSWORD`, `KUBE_CONFIG`).
3. Commit a sample application and prepare `Dockerfile` and `k8s/` manifests.

</details>

---

##  **Section 2: Continuous Integration (CI)**

<details>
<summary><strong>2.1 Build and Test Automation</strong></summary>

**Topics:**

* Writing a CI workflow to automate linting and unit tests
* Defining job dependencies (`needs:`)
* Using matrix builds for multiple environments
* Adding caching for dependencies

**Assignments:**

1. Create `.github/workflows/ci.yml` for automated test runs on PR or push.
2. Add dependency caching to speed up CI.
3. Configure job conditions for only running tests on changed files.

**Sample CI Workflow:**

```yaml
name: CI
on:
  push:
    branches: [ "main" ]
  pull_request:

jobs:
  test:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - name: Install dependencies
        run: pip install -r requirements.txt
      - name: Run unit tests
        run: pytest
```

</details>

---

## 🐳 **Section 3: Continuous Delivery (CD) – Docker Build & Push**

<details>
<summary><strong>3.1 Docker Build and Registry Push</strong></summary>

**Topics:**

* Building Docker images in GitHub Actions
* Authenticating to DockerHub or GitHub Container Registry
* Dynamic tagging (using commit SHA or version)
* Reusable workflows for multiple services

**Assignments:**

1. Create `.github/workflows/build.yml` for Docker build & push.
2. Use GitHub Secrets for Docker authentication.
3. Automate image tagging and push to the registry.

**Sample Build Workflow:**

```yaml
name: Build and Push Docker Image
on:
  push:
    branches: [ "main" ]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      
      - name: Login to DockerHub
        uses: docker/login-action@v3
        with:
          username: ${{ secrets.DOCKER_USERNAME }}
          password: ${{ secrets.DOCKER_PASSWORD }}
      
      - name: Build and Push Image
        uses: docker/build-push-action@v5
        with:
          context: .
          push: true
          tags: myrepo/myapp:${{ github.sha }}
```

</details>

---

## ☸️ **Section 4: Continuous Deployment – Kubernetes Automation**

<details>
<summary><strong>4.1 Kubernetes Deployment Workflow</strong></summary>

**Topics:**

* Deploying updated images to Kubernetes using `kubectl`
* Updating image tags dynamically in manifests
* Blue-Green or Rolling Deployments
* Applying manifests automatically post Docker build

**Assignments:**

1. Create `.github/workflows/deploy.yml` for Kubernetes deployment.
2. Store `KUBE_CONFIG` as a GitHub secret.
3. Automate rolling deployment to update the app image tag.

**Sample Deployment Workflow:**

```yaml
name: Deploy to Kubernetes
on:
  workflow_run:
    workflows: ["Build and Push Docker Image"]
    types:
      - completed

jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      
      - name: Setup kubectl
        uses: azure/setup-kubectl@v3
      
      - name: Configure kubeconfig
        run: |
          mkdir -p $HOME/.kube
          echo "${{ secrets.KUBE_CONFIG }}" > $HOME/.kube/config
      
      - name: Update Image and Deploy
        run: |
          kubectl set image deployment/myapp myapp=myrepo/myapp:${{ github.sha }}
          kubectl rollout status deployment/myapp
```

</details>

---

<details>
<summary><strong>4.2 Environment Promotion (Staging → Production)</strong></summary>

**Topics:**

* Using GitHub Environments (dev, stage, prod)
* Manual approvals for production deployment
* Workflow conditions for environment promotion
* Multi-cluster or namespace deployment strategies

**Assignments:**

1. Create environments with manual approvals in GitHub.
2. Add conditional deployment logic (`if: github.ref == 'refs/heads/main'`).
3. Test staging deployment before promoting to production.

</details>

---

## 🔐 **Section 5: Security, Observability, and Rollback**

<details>
<summary><strong>5.1 Security and Secrets Management</strong></summary>

**Topics:**

* Managing sensitive data with GitHub Secrets
* Integrating secret scanners and Docker image scanning (Trivy/Snyk)
* Enforcing signed commits and branch protection

**Assignments:**

1. Add Trivy scan before Docker push.
2. Use GitHub Secret Scanning to detect credentials.
3. Enable branch protection for CI/CD safety.

</details>

---

<details>
<summary><strong>5.2 Monitoring, Notifications, and Rollback</strong></summary>

**Topics:**

* Sending Slack/MS Teams notifications
* Monitoring deployment status and job failures
* Creating rollback workflows with GitHub Actions
* Automated rollback using `kubectl rollout undo`

**Assignments:**

1. Add Slack webhook notifications for pipeline completion.
2. Create a rollback workflow triggered manually (`workflow_dispatch`).
3. Document rollback steps for failed Kubernetes deployments.

</details>

---

## 🧠 **Section 6: Putting It All Together**

<details>
<summary><strong>6.1 Full End-to-End Pipeline</strong></summary>

**Topics:**

* Linking CI → CD → Deployment workflows together
* Chaining workflows using `workflow_run` triggers
* Visualizing pipeline in GitHub Actions dashboard
* Maintaining versioned workflows for microservices

**Assignments:**

1. Combine CI, Build, and Deploy into one orchestrated pipeline.
2. Document pipeline structure and triggers.
3. Demonstrate a successful deployment from Git push → K8s update.

</details>

---

</details>

---

###  **Cloud Computing Fundamentals & Azure Fundamentals**

<details>
<summary>📘 <strong>Module: Cloud Computing Fundamentals & Azure Fundamentals</strong></summary>

---

## 🧩 **Section 1: Cloud Computing Fundamentals**

<details>
<summary><strong>1.1 Introduction to Cloud Computing</strong></summary>

**Topics:**

* What is Cloud Computing?
* History and evolution of Cloud Computing
* Key characteristics: On-demand self-service, scalability, elasticity, and pay-as-you-go
* Benefits of Cloud Computing (cost efficiency, flexibility, global access, disaster recovery)

**Assignments:**

1. Write a short report on how Cloud Computing differs from traditional on-premises IT.
2. Identify three real-world companies using cloud technologies and describe their use cases.
3. Explain “pay-as-you-go” pricing with an example scenario.

</details>

---

<details>
<summary><strong>1.2 Types of Cloud Deployments</strong></summary>

**Topics:**

* Public Cloud
* Private Cloud
* Hybrid Cloud
* Community Cloud
* Choosing the right deployment model for different business needs

**Assignments:**

1. Create a comparison chart between Public, Private, and Hybrid clouds.
2. Provide a real-world use case for each deployment model.
3. Research and summarize which industries commonly use Hybrid Cloud models.

</details>

---

<details>
<summary><strong>1.3 Types of Cloud Services</strong></summary>

**Topics:**

* IaaS (Infrastructure as a Service)
* PaaS (Platform as a Service)
* SaaS (Software as a Service)
* FaaS (Function as a Service – brief introduction)
* Understanding the shared responsibility model

**Assignments:**

1. Create a diagram showing the difference between IaaS, PaaS, and SaaS.
2. Classify common services like Azure Virtual Machines, Azure App Service, and Microsoft 365 under correct categories.
3. Explain how responsibilities differ between Cloud Provider and Customer.

</details>

---

<details>
<summary><strong>1.4 Introduction to Microsoft Azure</strong></summary>

**Topics:**

* Overview of Microsoft Azure and global infrastructure
* Azure Regions, Availability Zones, and Resource Groups
* Key services offered by Azure: Compute, Storage, Networking, Databases, AI, and Security
* Benefits of using Microsoft Azure for businesses

**Assignments:**

1. Explore the [Azure Portal](https://portal.azure.com/) and list available global regions.
2. Identify 5 core Azure services and describe their purpose.
3. Write a paragraph on Azure’s global availability and fault tolerance strategy.

</details>

---

<details>
<summary><strong>1.5 Creating an Azure Account</strong></summary>

**Topics:**

* Step-by-step Azure account creation process
* Navigating the Azure Portal interface
* Understanding Azure Subscriptions and Billing
* Free-tier services and trial credits

**Assignments:**

1. Create a free Azure account and explore the portal dashboard.
2. Identify and note free-tier services available in your subscription.
3. Explore and summarize Azure pricing calculator usage.

</details>

---

## 🧱 **Section 2: Azure Services & Architecture**

<details>
<summary><strong>2.1 Azure Services Overview</strong></summary>

**Topics:**

* Azure Compute Services (VMs, App Services, AKS)
* Azure Storage (Blob, File, Queue, Disk)
* Azure Identity (Active Directory, Role-based access control - RBAC)
* Azure Monitoring and Management Tools

**Assignments:**

1. Create a virtual machine and connect via RDP/SSH.
2. Deploy an App Service and test it via public endpoint.
3. Explore Azure Storage options and upload a file to Blob storage.

</details>

---

<details>
<summary><strong>2.2 Resource Groups and Resource Management</strong></summary>

**Topics:**

* Understanding Resource Groups in Azure
* Creating and organizing Resources under Resource Groups
* Best practices for resource naming and tagging
* Managing resources via Azure Portal, CLI, and PowerShell

**Assignments:**

1. Create a Resource Group and deploy at least two resources under it.
2. Apply tagging conventions for better cost management.
3. Delete and restore resources using Azure Resource Manager (ARM).

</details>

---

<details>
<summary><strong>2.3 Azure ARM Template vs Bicep</strong></summary>

**Topics:**

* Introduction to Infrastructure as Code (IaC)
* Understanding Azure Resource Manager (ARM) templates
* Limitations of JSON-based ARM templates
* Introduction to Bicep: syntax, structure, and deployment workflow
* Comparison between ARM templates and Bicep

**Assignments:**

1. Deploy a simple resource (like a Storage Account) using an ARM template.
2. Convert an existing ARM template to Bicep format.
3. Write a small Bicep file to deploy an Azure Web App.

</details>

---

</details>

---

###  **Entra ID (Azure Active Directory)**

<details>
<summary> <strong>Module: Entra ID (Azure Active Directory)</strong></summary>

---

##  **Section 1: Azure Active Directory (AAD) Basics**

<details>
<summary><strong>1.1 Introduction to Entra ID / Azure AD</strong></summary>

**Topics:**

* What is Microsoft Entra ID (formerly Azure AD)?
* Importance of Identity and Access Management (IAM) in Azure
* Key components: Tenant, Directory, Identity, and Subscription
* Understanding authentication vs authorization
* Azure AD vs On-Premises AD

**Assignments:**

1. Create a brief comparison between Entra ID and traditional Active Directory.
2. Explore your Azure portal and identify the default tenant setup.
3. Explain the purpose of a Tenant ID and Directory ID in Azure.

</details>

---

<details>
<summary><strong>1.2 Managing Users, Groups, and Roles</strong></summary>

**Topics:**

* Creating and managing users in Entra ID
* Understanding user properties and authentication methods
* Creating and managing groups (Security groups and Microsoft 365 groups)
* Group-based access assignments
* Role assignments and group memberships

**Assignments:**

1. Create new users and assign them to groups in Entra ID.
2. Demonstrate how group-based access control simplifies management.
3. Document the difference between Security and Microsoft 365 groups.

</details>

---

##  **Section 2: Role-Based Access Control (RBAC)**

<details>
<summary><strong>2.1 Understanding RBAC Concepts</strong></summary>

**Topics:**

* What is Role-Based Access Control (RBAC)?
* Role assignment structure: Security principal, Role definition, and Scope
* Understanding scopes: Management Group, Subscription, Resource Group, Resource
* Built-in roles vs custom roles

**Assignments:**

1. Illustrate the RBAC model using a diagram showing principal → role → scope.
2. Create a list of common built-in roles in Azure.
3. Design a custom role definition in JSON format for restricted access.

</details>

---

<details>
<summary><strong>2.2 Assigning Roles using Azure Tools</strong></summary>

**Topics:**

* Assigning roles using Azure Portal
* Assigning roles using Azure PowerShell
* Assigning roles using Azure CLI
* Viewing and auditing role assignments

**Assignments:**

1. Assign the "Reader" role to a user via Azure Portal.
2. Use PowerShell to assign and remove a role at the Resource Group level.
3. Create a script using Azure CLI to list all role assignments in a subscription.

</details>

---

##  **Section 3: Subscriptions, Management, and Governance**

<details>
<summary><strong>3.1 Subscriptions and Management Groups</strong></summary>

**Topics:**

* What are Azure Subscriptions?
* Relationship between Tenant, Directory, and Subscription
* Management Groups hierarchy and use cases
* Organizing multiple subscriptions for enterprise governance

**Assignments:**

1. Create and organize multiple Resource Groups under one Subscription.
2. Set up a Management Group and move a Subscription under it.
3. Explain how Management Groups help in policy enforcement.

</details>

---

<details>
<summary><strong>3.2 Azure Policy and Blueprints (Basics)</strong></summary>

**Topics:**

* Introduction to Azure Policy
* Understanding Policy Definitions, Assignments, and Initiatives
* Common built-in policies (e.g., resource tagging, location restrictions)
* Introduction to Azure Blueprints and compliance automation

**Assignments:**

1. Assign a built-in Azure Policy to restrict resource creation by region.
2. Create a custom policy to enforce specific naming conventions.
3. Explore available Blueprints in the Azure portal and describe their purpose.

</details>

---

<details>
<summary><strong>3.3 Resource Locks and Tags</strong></summary>

**Topics:**

* Understanding Resource Locks: “CanNotDelete” and “ReadOnly”
* Applying and managing locks through Azure Portal, CLI, and PowerShell
* Importance of Tags for cost management and governance
* Applying and inheriting tags across resources

**Assignments:**

1. Apply a lock to a critical resource and test its effect.
2. Add tags to resources for cost tracking.
3. Write a PowerShell script to list all tags within a Resource Group.

</details>

---

</details>

---



###  **Azure Networking Basics**

<details>
<summary> <strong>Module: Azure Networking Fundamentals</strong></summary>

---

##  **Section 1: Introduction to Azure Networking**

<details>
<summary><strong>1.1 Fundamentals of Cloud Networking</strong></summary>

**Topics:**

* What is cloud networking?
* Importance of virtual networks in cloud environments
* Comparison: On-premises networking vs Azure networking
* Understanding CIDR notation and IP addressing basics
* Overview of Azure Virtual Network (VNet)

**Assignments:**

1. Define the difference between traditional LAN and Azure VNet.
2. Create a diagram of a simple Azure network with a subnet and virtual machine.
3. Explain the concept of CIDR notation and calculate an IP range for a /24 network.

</details>

---

<details>
<summary><strong>1.2 Azure Virtual Network (VNet) and Subnets</strong></summary>

**Topics:**

* Overview of Azure VNet architecture
* Creating and configuring VNets and subnets
* Address spaces and subnet delegation
* Public vs Private IP addressing
* Network Interface Cards (NICs) and IP configuration

**Assignments:**

1. Create a VNet with two subnets (Frontend and Backend).
2. Assign static private IP addresses to a virtual machine.
3. Demonstrate subnet delegation using Azure Portal.

</details>

---

##  **Section 2: Network Security and Control**

<details>
<summary><strong>2.1 Network Security Groups (NSG)</strong></summary>

**Topics:**

* What is a Network Security Group?
* Inbound and outbound security rules
* NSG priorities and rule processing order
* Applying NSGs to subnets and NICs
* Troubleshooting NSG rules using Azure Network Watcher

**Assignments:**

1. Create an NSG and allow only RDP (port 3389) from a specific IP.
2. Associate the NSG with a subnet and test connectivity.
3. Use Network Watcher to monitor NSG flow logs.

</details>

---

<details>
<summary><strong>2.2 Azure Firewall and Application Gateway (Intro)</strong></summary>

**Topics:**

* Difference between NSG, Azure Firewall, and Application Gateway
* Overview of Azure Firewall capabilities
* Application Gateway for Layer 7 load balancing and WAF (Web Application Firewall)
* When to use which: NSG vs Firewall vs Application Gateway

**Assignments:**

1. Compare Azure Firewall and Application Gateway in a tabular format.
2. Design a simple network diagram using both NSG and Firewall.
3. Enable WAF in an Application Gateway and document the steps.

</details>

---

##  **Section 3: Connectivity Between Networks**

<details>
<summary><strong>3.1 VNet Peering and Service Endpoints</strong></summary>

**Topics:**

* What is VNet Peering?
* Peering configuration (same region and cross-region)
* Understanding Service Endpoints and Private Links
* Differences between VNet Peering and VPN connections

**Assignments:**

1. Peer two VNets in the same region.
2. Implement VNet Peering across regions and verify connectivity.
3. Enable a Service Endpoint for Azure Storage and test access.

</details>

---

<details>
<summary><strong>3.2 VPN Gateway and ExpressRoute (Overview)</strong></summary>

**Topics:**

* Site-to-Site VPN overview
* Point-to-Site VPN overview
* ExpressRoute fundamentals
* Azure VPN Gateway SKUs and use cases
* Hybrid connectivity scenarios

**Assignments:**

1. Create a Point-to-Site VPN using Azure Portal.
2. Describe the difference between S2S and P2S VPN connections.
3. Research the benefits of ExpressRoute for enterprise networks.

</details>

---

##  **Section 4: Monitoring and Troubleshooting**

<details>
<summary><strong>4.1 Azure Network Watcher</strong></summary>

**Topics:**

* What is Azure Network Watcher?
* Connection troubleshooting tools: Connection Monitor, IP Flow Verify, Next Hop
* Network topology visualization
* NSG flow logs and packet capture

**Assignments:**

1. Enable Network Watcher in your subscription.
2. Run a connection monitor between two VMs and capture results.
3. Use IP Flow Verify to diagnose a blocked connection.

</details>

---

<details>
<summary><strong>4.2 Best Practices in Azure Networking</strong></summary>

**Topics:**

* Designing VNets for scalability and performance
* Naming conventions and tagging standards
* Security best practices for subnets and NSGs
* Cost optimization for Azure networking components

**Assignments:**

1. Create a best practices checklist for Azure networking.
2. Review Azure Advisor recommendations for your network setup.
3. Document an example of a secure multi-tier network design.

</details>

---

</details>



## ☁️ **Azure Storage, Key Vault, and Web App**

This version maintains the same style and structure as your earlier modules (Python, Git, Docker, Azure Networking, etc.) — suitable for structured learning paths or LMS integration.

---


---

###  **Azure Storage, Key Vault, Web App, and DNS Zone**

<details>
<summary>📘 <strong>Module: Azure Storage, Key Vault, Web App, and DNS Zone</strong></summary>

---

## **Section 1: Azure Storage Fundamentals**

<details>
<summary><strong>1.1 Azure Storage Account Overview</strong></summary>

**Topics:**

* What is Azure Storage?
* Storage account types: General-purpose v2, Blob, File, Queue, Table
* Standard vs Premium storage
* Redundancy options (LRS, ZRS, GRS, RA-GRS)
* Access endpoints and keys

**Assignments:**

1. Create a storage account in Azure.
2. Compare redundancy types (LRS vs GRS).
3. Identify endpoints and access keys from the portal.

</details>

---

<details>
<summary><strong>1.2 Blob Storage Management</strong></summary>

**Topics:**

* Blob types (Block, Append, Page)
* Containers and access levels
* Hot, Cool, and Archive tiers
* Blob lifecycle policies and versioning
* Managing blobs via Portal, CLI, PowerShell

**Assignments:**

1. Create a blob container and upload data.
2. Configure lifecycle management for tier transitions.
3. Enable blob versioning and perform recovery.

</details>

---

<details>
<summary><strong>1.3 File Shares and Azure Files</strong></summary>

**Topics:**

* Difference between Azure Files and Blob Storage
* Creating and mounting File Shares
* SMB and NFS support
* Snapshots and backup
* Managing access permissions

**Assignments:**

1. Create and mount an Azure File Share to a VM.
2. Upload and manage files using PowerShell.
3. Test restoring data using a snapshot.

</details>

---

<details>
<summary><strong>1.4 Secure Access and Tools</strong></summary>

**Topics:**

* Shared Access Signatures (SAS)
* Azure AD Authentication for storage
* AzCopy and Storage Explorer
* Role-based access for Storage Accounts

**Assignments:**

1. Generate a SAS token for limited access.
2. Use AzCopy to upload and download data.
3. Explore storage account roles in IAM.

</details>

---

##  **Section 2: Azure Key Vault**

<details>
<summary><strong>2.1 Key Vault Basics and Use Cases</strong></summary>

**Topics:**

* What is Azure Key Vault?
* Managing **Secrets**, **Keys**, and **Certificates**
* Integration with Azure services
* Key Vault security model

**Assignments:**

1. Create a Key Vault.
2. Add and retrieve a secret.
3. Document the difference between secrets and certificates.

</details>

---

<details>
<summary><strong>2.2 Access Policies and Security</strong></summary>

**Topics:**

* Key Vault Access Policies
* RBAC vs Access Policies
* Networking: Firewall and Private Endpoints
* Logging and monitoring

**Assignments:**

1. Assign a secret read policy to a user.
2. Enable firewall and restrict access by VNet.
3. Configure Key Vault diagnostic logs.

</details>

---

<details>
<summary><strong>2.3 Secret Versioning and Automation</strong></summary>

**Topics:**

* Secret versioning and rollback
* Secret rotation strategies
* Integration with Azure Functions or Logic Apps

**Assignments:**

1. Create multiple secret versions and observe behavior.
2. Implement automated rotation using a Function App.
3. Retrieve secrets using CLI or PowerShell.

</details>

---

##  **Section 3: Azure Web App and Function Apps**

<details>
<summary><strong>3.1 Azure Web App Fundamentals</strong></summary>

**Topics:**

* What is Azure Web App?
* App Service Plan and pricing tiers
* Deploying apps via GitHub or DevOps pipelines
* Application settings and scaling

**Assignments:**

1. Deploy a sample web app using Azure Portal.
2. Connect GitHub for continuous deployment.
3. Test scaling by adjusting App Service Plan.

</details>

---

<details>
<summary><strong>3.2 Deployment Slots and Configuration</strong></summary>

**Topics:**

* Deployment slot concepts
* Staging vs production environments
* Slot swapping and rollback
* Configuration management

**Assignments:**

1. Create a staging slot.
2. Perform a slot swap and verify the change.
3. Configure different app settings per slot.

</details>

---

<details>
<summary><strong>3.3 Function Apps Overview</strong></summary>

**Topics:**

* Azure Function Apps and serverless architecture
* Supported triggers (HTTP, Blob, Timer, etc.)
* Consumption vs Premium plans
* Monitoring with Application Insights

**Assignments:**

1. Create a Function App with HTTP trigger.
2. Log requests to Application Insights.
3. Compare pricing models for Function Apps.

</details>

---

<details>
<summary><strong>3.4 Web App Networking and Security</strong></summary>

**Topics:**

* Private Endpoints and VNet integration
* Access Restrictions and IP filtering
* Enabling HTTPS and custom domains
* Managed Identity with Key Vault

**Assignments:**

1. Configure HTTPS for a web app.
2. Set up a private endpoint for secure access.
3. Use Managed Identity to access a Key Vault secret.

</details>

---

##  **Section 4: Azure DNS Zone**

<details>
<summary><strong>4.1 Introduction to Azure DNS</strong></summary>

**Topics:**

* What is DNS and why it matters
* Azure DNS overview and use cases
* Public vs Private DNS Zones
* How Azure DNS integrates with VNets

**Assignments:**

1. Define key DNS concepts (A, CNAME, TXT, MX, NS).
2. Identify the difference between public and private zones.
3. Diagram a basic Azure DNS integration scenario.

</details>

---

<details>
<summary><strong>4.2 Managing DNS Zones and Records</strong></summary>

**Topics:**

* Creating and managing DNS Zones in Azure
* Adding and modifying DNS records (A, CNAME, MX, TXT)
* Delegating DNS domains to Azure DNS
* DNS propagation and troubleshooting

**Assignments:**

1. Create a DNS zone and add A/CNAME records.
2. Delegate a domain to Azure DNS and test resolution.
3. Use nslookup and dig commands to verify propagation.

</details>

---

<details>
<summary><strong>4.3 Private DNS Zones and Integration</strong></summary>

**Topics:**

* Creating private DNS zones
* Linking private zones with VNets
* Split-horizon DNS concept
* Managing name resolution within VNets

**Assignments:**

1. Create a private DNS zone and link it to a VNet.
2. Configure VM name resolution using a private DNS zone.
3. Document the differences between Azure DNS and Private Resolver.

</details>

---

</details>

---


---

###  **Terraform with Azure**

<details>
<summary>📘 <strong>Module: Terraform with Azure (Infrastructure as Code)</strong></summary>

---

## 🌱 **Section 1: Infrastructure as Code (IaC) Fundamentals**

<details>
<summary><strong>1.1 Introduction to IaC</strong></summary>

**Topics:**

* What is Infrastructure as Code (IaC)?
* Benefits of IaC in modern cloud environments
* Declarative vs Imperative infrastructure management
* Common IaC tools overview: Terraform, ARM Templates, Bicep, CloudFormation

**Assignments:**

1. Write a short note on benefits of IaC.
2. Compare declarative vs imperative infrastructure management.
3. Identify three use cases where IaC can improve DevOps workflows.

</details>

---

<details>
<summary><strong>1.2 Terraform vs CloudFormation</strong></summary>

**Topics:**

* Overview of Terraform
* Overview of AWS CloudFormation
* Comparison of cross-platform support
* Advantages of using Terraform for Azure environments

**Assignments:**

1. Create a comparison chart between Terraform and CloudFormation.
2. Explain why Terraform is preferred for multi-cloud deployments.
3. Identify providers Terraform can work with beyond AWS and Azure.

</details>

---

## ⚙️ **Section 2: Terraform Installation and Configuration**

<details>
<summary><strong>2.1 Installing Terraform</strong></summary>

**Topics:**

* Installing Terraform on Windows, macOS, and Linux
* Verifying installation and environment setup
* Understanding Terraform CLI commands

**Assignments:**

1. Install Terraform and verify installation using `terraform -version`.
2. Configure Terraform path variables on your system.
3. Run a test command (`terraform --help`) to explore available commands.

</details>

---

<details>
<summary><strong>2.2 Setting up Azure CLI and Authentication</strong></summary>

**Topics:**

* Installing Azure CLI
* Authenticating with Azure CLI (`az login`)
* Configuring Terraform credentials for Azure
* Understanding Service Principal authentication

**Assignments:**

1. Install and authenticate Azure CLI.
2. Create a Service Principal for Terraform with Contributor role.
3. Store Azure credentials securely for Terraform execution.

</details>

---

## 🧩 **Section 3: Terraform Core Concepts**

<details>
<summary><strong>3.1 Understanding Terraform Providers and Resources</strong></summary>

**Topics:**

* What are Terraform providers?
* How Terraform interacts with Azure through `azurerm` provider
* Understanding resources and resource blocks
* Provider configuration examples

**Assignments:**

1. Configure the AzureRM provider in a `.tf` file.
2. List the commonly used Azure resource types in Terraform.
3. Explain how providers enable cross-cloud management.

</details>

---

<details>
<summary><strong>3.2 Terraform Configuration Files (.tf)</strong></summary>

**Topics:**

* Structure of a Terraform project
* Understanding `.tf` and `.tfstate` files
* Using variables (`variables.tf`) and outputs (`outputs.tf`)
* Defining dependencies between resources

**Assignments:**

1. Create a Terraform configuration with variables and outputs.
2. Organize Terraform code into separate files for clarity.
3. Document the purpose of each Terraform file type.

</details>

---

<details>
<summary><strong>3.3 Terraform Workflow Commands</strong></summary>

**Topics:**

* Core commands: `terraform init`, `plan`, `apply`, and `destroy`
* Understanding execution plans
* Handling errors and rollbacks
* Best practices for safe apply and destroy

**Assignments:**

1. Initialize Terraform in a new project (`terraform init`).
2. Generate a plan and review the output.
3. Apply the configuration to deploy a simple Azure resource.

</details>

---

<details>
<summary><strong>3.4 Terraform State Management</strong></summary>

**Topics:**

* What is the Terraform state file (`terraform.tfstate`)?
* Importance of state tracking
* Remote state management (Azure Storage backend)
* Locking and consistency in state files

**Assignments:**

1. Inspect your local state file.
2. Configure remote state storage in Azure Blob Storage.
3. Explain benefits of using remote state in team environments.

</details>

---

##  **Section 4: Advanced Terraform Concepts**

<details>
<summary><strong>4.1 Terraform Modules and Reusability</strong></summary>

**Topics:**

* What are Terraform modules?
* Module structure and best practices
* Using public modules from Terraform Registry
* Creating and using local modules

**Assignments:**

1. Create a custom module for deploying a VNet.
2. Use a module from Terraform Registry in your configuration.
3. Document the advantages of modular Terraform design.

</details>

---

<details>
<summary><strong>4.2 Terraform Lifecycle and Dependencies</strong></summary>

**Topics:**

* Resource lifecycle meta-arguments (`create_before_destroy`, `prevent_destroy`)
* Handling resource dependencies using `depends_on`
* Lifecycle hooks and order of operations

**Assignments:**

1. Add lifecycle rules to protect critical resources.
2. Demonstrate use of `depends_on` between two resources.
3. Simulate dependency resolution using `terraform plan`.

</details>

---

<details>
<summary><strong>4.3 Workspaces for Multi-Environment Management</strong></summary>

**Topics:**

* Purpose of Terraform Workspaces
* Managing non-prod, UAT, and production environments
* Workspace switching and isolation of state files

**Assignments:**

1. Create multiple workspaces (`dev`, `prod`).
2. Deploy resources in different workspaces and compare states.
3. Explain how workspaces simplify environment separation.

</details>

---

##  **Section 5: Terraform CI/CD Integration**

<details>
<summary><strong>5.1 Terraform with GitHub Actions</strong></summary>

**Topics:**

* Automating Terraform with CI/CD pipelines
* Setting up GitHub Actions for Terraform
* Workflow for plan and apply approval gates
* Managing secrets and credentials securely in pipelines

**Assignments:**

1. Create a GitHub Actions workflow for Terraform.
2. Automate plan and apply steps using environment approvals.
3. Store Terraform state remotely and integrate with pipeline.

</details>

---

---

##  **Section 6: Hands-on Labs with Azure**

<details>
<summary><strong>6.1 Real-World Terraform Practice</strong></summary>

**Lab Tasks:**

* Create an Azure Resource Group using Terraform
* Deploy a Virtual Network (VNet) and Subnet
* Launch a Virtual Machine and attach a Public IP
* Create and configure a Key Vault
* Provision a Storage Account
* Output resource information using Terraform outputs

**Assignments:**

1. Implement the full Terraform configuration for a simple 3-tier setup.
2. Store Terraform state remotely in Azure Storage.
3. Share your Terraform files via GitHub and integrate with CI/CD.

</details>

---

</details>

---


