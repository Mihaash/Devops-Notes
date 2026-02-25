# Devops-Notes
## WHAT IS CLOUD COMPUTING

Cloud Computing is the delivery of computing services over the internet (“the cloud”), instead of using a local computer or on-premise server.

**These services include:**

Servers (virtual machines),

Storage (files, databases, backups),

Networking (load balancers, firewalls, VPNs),

Software (apps and development tools),

Analytics & AI services.
# Software Development Life Cycle (SDLC)

**SDLC** stands for **Software Development Life Cycle**.  
It is a **step-by-step process** used by software developers and organizations to **plan, design, build, test, and deploy high-quality software**.

---

## SDLC Phases

| **Phase**       | **Purpose**                                                    | **Main Deliverables**                            |
|------------------|----------------------------------------------------------------|--------------------------------------------------|
| **1. Requirements** | Collect and define what the user wants.                       | SRS (Software Requirement Specification)         |
| **2. Analysis**     | Study the feasibility, risks, and resources needed.           | Feasibility Report, Project Plan                 |
| **3. Design**       | Plan how the software will work (architecture, UI, database). | HLD (High-Level Design), LLD (Low-Level Design)  |
| **4. Development**  | Write the actual code and integrate modules.                  | Source Code, Unit Tests                          |
| **5. Testing**      | Verify that the software works correctly and is bug-free.     | Test Reports, Bug Logs                           |
| **6. Deployment**   | Deliver and install the software for end users.               | Release Notes, Deployment Logs                   |
| **7. Maintenance**  | Update, fix bugs, and improve performance after release.      | Patches, Updated Versions                        |

---

# SDLC Models

## 1. Waterfall Model

**Definition:**  
The Waterfall Model is a **sequential SDLC approach** where each phase must be completed before moving to the next:  
**Requirements → Design → Development → Testing → Deployment → Maintenance**.  
It’s like a “step-by-step flow” of water — once a phase is done, you **can’t go back**.

**Advantages:**  
- ✅ Simple and easy to understand.  
- ✅ Clearly defined stages and deliverables.  
- ✅ Good for projects with well-defined, stable requirements.  
- ✅ Easier to manage due to its structured approach.  

**Disadvantages:**  
- ❌ No flexibility — difficult to go back and change anything.  
- ❌ Testing happens late (after development).  
- ❌ Not suitable for complex or evolving projects.  
- ❌ High risk and cost if requirements change mid-way.  

---

## 2. Agile Model

**Definition:**  
Agile is an **iterative and incremental SDLC model** focusing on **customer collaboration, flexibility, and continuous delivery**.  
Work is divided into **sprints** (short cycles, typically 1–4 weeks).

**Advantages:**  
- ✅ Highly flexible and adaptive to changes.  
- ✅ Continuous feedback from stakeholders.  
- ✅ Early and frequent delivery of working software.  
- ✅ Encourages teamwork, communication, and collaboration.  
- ✅ Improves product quality through regular testing.  

**Disadvantages:**  
- ❌ Requires experienced and self-organized teams.  
- ❌ Documentation can be minimal or inconsistent.  
- ❌ Scope creep (frequent changes can cause confusion).  
- ❌ Difficult for large, distributed teams without coordination.  

---

## 3. DevOps Model

**Definition:**  
DevOps combines **Development (Dev)** and **Operations (Ops)** to ensure **continuous integration, testing, delivery, and monitoring**.  
Its goal is to **automate and shorten the software delivery cycle** using tools like **Jenkins, Docker, Kubernetes, Git, Ansible**, etc.

**Advantages:**  
- ✅ Faster software delivery through automation (CI/CD).  
- ✅ Better collaboration between developers and operations teams.  
- ✅ Continuous monitoring and feedback improve reliability.  
- ✅ Reduced time to market and higher customer satisfaction.  
- ✅ Easier to detect and fix issues early.  

# DevOps Stages 

| **Stage**                 | **Description**                                             | **Activities**                                                                 | **Common Tools**                                  |
|----------------------------|-------------------------------------------------------------|-------------------------------------------------------------------------------|--------------------------------------------------|
| **1. Planning**            | Define requirements, goals, and features                  | Sprint planning, backlog creation, user stories, resource allocation         | Jira, Trello, Azure Boards, Confluence          |
| **2. Coding / Development**| Write application code based on requirements             | Code implementation, version control, code review                             | Git, GitHub, GitLab, Bitbucket                  |
| **3. Continuous Integration (CI)** | Merge code frequently and automatically build/test     | Automated builds, unit testing, static code analysis                          | Jenkins, Travis CI, CircleCI, GitLab CI/CD      |
| **4. Continuous Testing**  | Automatically test the application for quality           | Unit testing, integration testing, functional testing, security testing       | Selenium, JUnit, TestNG, SonarQube, Postman    |
| **5. Continuous Deployment / Delivery (CD)** | Automatically deploy to staging/production        | Deployment automation, environment configuration, rollback planning           | Docker, Kubernetes, Ansible, Puppet, Chef      |
| **6. Continuous Monitoring** | Monitor application performance and infrastructure     | Error logging, performance monitoring, security monitoring, incident response | Prometheus, Grafana, ELK Stack, Nagios, Splunk |
| **7. Continuous Feedback** | Collect insights from users and stakeholders             | User analytics, bug reports, performance metrics, monitoring insights         | Jira, Bugzilla, Google Analytics, Feedback portals |


# Jenkins Overview

**Jenkins** is an **open-source automation server** used to **build, test, and deploy software continuously** — part of what’s known as **CI/CD (Continuous Integration / Continuous Delivery)**.

---

## What Jenkins Does

Jenkins automates repetitive tasks in software development:

- **Builds** your source code (e.g., from GitHub)
- **Runs tests** automatically
- **Deploys** applications to servers or cloud
- **Integrates** with hundreds of DevOps tools

---

## How Jenkins Works (Simplified Flow)

1. Developer commits code → e.g., pushes to GitHub  
2. Jenkins detects the change (via webhook or polling)  
3. Build starts automatically  
4. Jenkins executes defined build steps (like compiling code, running tests)  
5. If successful → it **deploys** the app to test or production  
6. If failed → Jenkins **alerts the team** via email/Slack  

---
**SonarQube** continuously inspects your source code to detect errors, enforce coding standards, and measure technical debt.  
It supports many languages like **Java, Python, JavaScript, C#, PHP, C/C++, Go, and more.**

---

## What SonarQube Does

SonarQube analyzes code for:

-  **Bugs** – Code that can cause malfunction.  
-  **Vulnerabilities** – Security risks like SQL injection or XSS.  
-  **Code Smells** – Poor design choices that affect maintainability.  
-  **Duplications** – Repeated blocks of code.  
-  **Code Coverage** – How much of your code is covered by tests.  
- **Technical Debt** – Estimated time to fix all maintainability issues.  

## DevOps Lifecycle:

Plan: Jira, Trello
Code: Git, GitHub, GitLab
Build: Jenkins, Maven
Test: Selenium, JUnit
Release: Docker, Kubernetes
Deploy: Ansible, Terraform
Operate: Kubernetes, AWS ECS
Monitor: Prometheus, Grafana, ELK Stack

