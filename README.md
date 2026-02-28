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


## DAY 03(AWS)
## What is Cloud?

**Cloud (Cloud Computing)** means using **remote servers on the internet** to store data, run applications, and process information — instead of using your own local computer.

## What is AWS?

Amazon Web Services (AWS) is a **cloud computing platform** by Amazon that lets you:

- Create virtual servers
    
- Store data
    
- Host websites
    
- Run applications
    
- Build security systems
    
- Deploy DevOps pipelines
    

Instead of buying physical servers, you **rent infrastructure online**.
# EC2 (Elastic Compute Cloud)

Amazon Web Services EC2 = **Virtual Server in the cloud**

It is just like:

- Your laptop
    
- But running inside AWS data center
    

You can:

- Install Linux
    
- Install tools (Nmap, Docker, etc.)
    
- Host websites
    
- Run scanners
    
- Deploy apps

# VPC (Virtual Private Cloud)

VPC = **Your own private network inside AWS**

Think of it like:

>  A private apartment building in the cloud

Inside VPC you control:

- IP ranges
    
- Subnets
    
- Routing
    
- Firewalls
#  Subnet

Subnet = Small network inside VPC.

Two types:

###  Public Subnet

- Has internet access
    
- Used for:
    
    - Web servers
        
    - Bastion host
        
    - Public EC2
        

###  Private Subnet

- No direct internet
    
- Used for:
    
    - Database
        
    - Backend servers
        
    - Internal apps
# Internet Gateway (IGW)

IGW = Allows VPC to connect to the Internet.

Without IGW:  
❌ No internet access

With IGW:  
✅ Public EC2 can access internet

## What is S3?

Amazon Web Services **S3 (Simple Storage Service)** is a cloud storage service used to store and retrieve **any amount of data** from anywhere on the internet.

>  Google Drive — but for developers and companies.

---

# 🏗 How S3 Works

S3 stores data in:

-  **Buckets** → like folders
    
-  **Objects** → files inside bucket
    
-  Metadata → information about files

# S3 Storage Classes
| Class                 | Use Case                    |
|-----------------------|----------------------------|
| Standard              | Frequently accessed        |
| Intelligent-Tiering   | Auto cost optimization     |
| Standard-IA           | Rarely accessed            |
| Glacier               | Archive                    |
| Glacier Deep Archive  | Long-term backup           |

# AWS Service Models

##  IaaS — Infrastructure as a Service

You get:

- Virtual machines
    
- Storage
    
- Networking
    

You manage:

- OS
    
- Applications
    
- Security patches
    

AWS gives:

- Hardware
    
- Virtualization
    
- Data center
    

### AWS Examples:

- EC2
    
- EBS
    
- VPC
##  PaaS — Platform as a Service

You get:

- Platform to deploy apps
    
- Managed runtime
    
- Managed infrastructure
    

You manage:

- Application code only
    

AWS manages:

- OS
    
- Server
    
- Scaling
    

### AWS Examples:

- Elastic Beanstalk
    
- Lambda
    
- RDS
##  SaaS — Software as a Service

You just use the software.

You manage:

- Nothing technical
    

Provider manages:

- Everything
    

Examples (not directly AWS services):

- Gmail
    
- Microsoft 365
    
- Slack
#  Compute Services

Used to run applications and servers.

- **EC2** → Virtual machines
    
- **Lambda** → Run code without servers
    
- **Elastic Beanstalk** → Deploy apps easily
    
- **ECS / EKS** → Run Docker & Kubernetes
    

 Example: Hosting your vulnerability scanner on EC2.

---

#  Storage Services

Used to store data.

- **S3** → Object storage
    
- **EBS** → Hard disk for EC2
    
- **EFS** → Shared file storage
    
- **Glacier** → Archive storage
    

 Example: Store logs or reports in S3.

---

#  Database Services

Managed databases.

- **RDS** → MySQL, PostgreSQL, etc.
    
- **DynamoDB** → NoSQL database
    
- **Aurora** → High-performance database
    
- **Redshift** → Data warehouse
    

 Example: Store user data in RDS.

---

# Networking Services

Control traffic and connectivity.

- **VPC** → Private network
    
- **Route 53** → DNS service
    
- **CloudFront** → CDN
    
- **Elastic Load Balancer (ELB)** → Distribute traffic
    

 Example: Public subnet + private subnet inside VPC.

---

# Security Services (Very Important )

- **IAM** → Access control
    
- **CloudTrail** → Logs API activity
    
- **GuardDuty** → Threat detection
    
- **WAF** → Web firewall
    
- **Shield** → DDoS protection
    
- **KMS** → Encryption keys
    

 Used in SOC & Cloud Security roles.

---

# Monitoring & DevOps

- **CloudWatch** → Monitoring & logs
    
- **CodePipeline** → CI/CD
    
- **CodeBuild** → Build automation
    
- **CodeDeploy** → Deployment automation


## What is CIDR?

**CIDR (Classless Inter-Domain Routing)** is a method used in IP networking to allocate IP addresses and define network ranges more efficiently than the old class-based system (Class A, B, C).

It helps in:

- Reducing wasted IP addresses
    
- Controlling network size
    
- Improving routing efficiency

## CIDR Quick Table
| CIDR | Subnet Mask       | Total IPs    | Usable Hosts   |
|------|-------------------|-------------|---------------|
| /8   | 255.0.0.0         | 16,777,216  | 16,777,214    |
| /16  | 255.255.0.0       | 65,536      | 65,534        |
| /24  | 255.255.255.0     | 256         | 254           |
| /30  | 255.255.255.252   | 4           | 2             |

![aws](images/day3/VPC.png)


## Create Subnet 1

- VPC → Select your VPC
    
- Subnet name → `mysub1`
    
- Availability Zone → us-east-1a (example)
    
- IPv4 CIDR →
    
    10.0.1.0/24
    
- Create subnet
    

---

## Create Subnet 2

- VPC → Same VPC
    
- Subnet name → `mysub2`
    
- Availability Zone → us-east-1b (recommended different AZ)
    
- IPv4 CIDR →
    
    10.0.2.0/24
    
- Create
![aws](images/day3/VPC2.png)

# Step 1: Go to Route Tables

AWS Console → VPC → Route Tables

You will see a default route table.

---

# Step 2: Add Internet Route

1. Select your Route Table (the one associated with your VPC)
    
2. Go to **Routes tab**
    
3. Click **Edit routes**
    
4. Add route:
    

Destination:

0.0.0.0/0

![aws](images/day3/internetgateway.png)

#  Enable Auto Public IP

Go to:

VPC → Subnets → testing-sub-01  
Actions → Edit subnet settings

Enable:  
✔ Auto-assign public IPv4 address
![SSH](images/day3/EC2.png)

![aws](images/day3/internetgateway.png)

- Instance state → **Running**
    
- Instance type → `t3.micro`
    
- Public IP → **44.195.35.72**
    
- Private IP → 11.0.2.98
    
- Region → **us-east-1 (N. Virginia)**

![aws](images/day3/EC2-1.png)

- Connected to EC2 (Ubuntu)
    
-  Installed Apache
    
-  Navigated to `/var/www/html`
    
-  Verified `index.html` exists
Add this rule:

|Type|Protocol|Port|Source|
|---|---|---|---|
|HTTP|TCP|80|0.0.0.0/0|

![aws](images/day3/create-file.png)

sudo nano /var/www/html/index.html
![aws](images/day3/running.png)



## DAY 04
##  What is Amazon S3?
**Amazon S3 (Simple Storage Service)** is a cloud storage service provided by **Amazon Web Services (AWS)** that lets you **store and retrieve any amount of data from anywhere**.
> S3 is an **object storage service** used to store files like:
# AWS S3 Storage Classes Comparison

| Storage Class | Best For | Storage Cost | Retrieval Cost | Access Speed | Availability | Stored In |
|---------------|----------|--------------|----------------|--------------|--------------|-----------|
| S3 Standard | Frequently used data | High | No | Milliseconds | 99.99% | Multi-AZ |
| S3 Intelligent-Tiering | Unknown access pattern | Medium | Small monitoring fee | Milliseconds | 99.9% | Multi-AZ |
| S3 Standard-IA | Rare access but fast needed | Lower | Yes | Milliseconds | 99.9% | Multi-AZ |
| S3 One Zone-IA | Non-critical rare data | Even lower | Yes | Milliseconds | 99.5% | Single AZ |
| S3 Glacier Instant Retrieval | Archive but instant access | Cheap | Yes | Milliseconds | 99.9% | Multi-AZ |
| S3 Glacier Flexible Retrieval | Long-term archive | Very cheap | Yes | Minutes–Hours | 99.99% durability | Multi-AZ |
| S3 Glacier Deep Archive | 7–10 year backup | Cheapest | Yes | 12+ Hours | 99.99% durability | Multi-AZ |
- Images
    
- Videos
    
- Backups
    
- Logs
    
- Website files
    
- Big data files


![aws](images/day4/Screenshot_2026-02-26_12.27.08.png)

![aws](images/day4/Screenshot_2026-02-26_12.28.28.png)
- Bucket name: **testing-application06**
    
- Region: **us-east-1**
    
- It is empty (no objects uploaded yet)
#  Step 1: Upload index.html

Click **Upload → Add files**
After upload, you should see:

#  Step 2: Enable Static Website Hosting

Go to:

**Properties → Static website hosting → Edit**
# Disable Block Public Access 

**Permissions → Block public access**

Block all public access

![aws](images/day4/Screenshot_2026-02-26_12.30.46.png)
![aws](images/day4/Screenshot_2026-02-26_12.32.44.png)
![aws](images/day4/Screenshot_2026-02-26_12.33.18.png)
![aws](images/day4/Screenshot_2026-02-26_12.33.27.png)
![aws](images/day4/Screenshot_2026-02-26_12.34.09.png)
![aws](images/day4/Screenshot_2026-02-26_12.34.23.png)
![aws](images/day4/Screenshot_2026-02-26_12.34.39.png)
![aws](images/day4/Screenshot_2026-02-26_12.35.59.png)
- One image → **Public**
    
- 🔒 One image → **Private**

![aws](images/day4/Screenshot_2026-02-26_12.37.06.png)
![aws](images/day4/Screenshot_2026-02-26_12.37.16.png)



![aws](images/day4/Screenshot_2026-02-26_12.38.45.png)
- For **Everyone (public access)** → ☑ Read is checked

![aws](images/day4/Screenshot_2026-02-26_12.37.16.png)
✅ This file is now PRIVATE  
❌ Not accessible publicly  
❌ Will return 403 if accessed directly


![aws](images/day4/Screenshot_2026-02-26_12.38.52.png)
![aws](images/day4/Screenshot_2026-02-26_12.39.12.png)
aws s3 cp 04f821c58a65f87cbac60022bb00b2b4.jpg s3://testing-cli06/
- file is uploaded successfully via CLI.
![aws](images/day4/Screenshot_2026-02-26_15.11.40.png)
![aws](images/day4/Screenshot_2026-02-26_16.04.18.png)


## DAY 5

# What is Git?

**Git** is a **version control system (VCS)**.

It is a tool used to:

- Track changes in code
    
- Maintain version history
    
- Work with branches
    
- Collaborate safely
    
- Restore older versions
    

Git works on your local computer.



Edit file
   ↓
Working Directory
   ↓ (git add)
Staging Area
   ↓ (git commit)
Local Repository
   ↓ (git push)
Remote Repository

git

---

# What is `git init`?

`git init` is the command used to:

> Initialize (start) a new Git repository in a folder.

![git](images/day5/Screenshot_2026-02-27_11.34.48.png)

`git status` is a command used to:

> Show the current state of your working directory and staging area.
![git](images/day5/Screenshot_2026-02-27_11.35.39.png)

`git log` is a command used to:

> Show the commit history of your Git repository.

![git](images/day5/Screenshot_2026-02-27_11.36.27.png)
![git](images/day5/Screenshot_2026-02-27_11.52.01.png)

git remote add origin
> Connect your local Git repository to a remote repository (like GitHub).
git remote add origin <repository-URL>
![git](images/day5/Screenshot_2026-02-27_11.54.33.png)
![git](images/day5/Screenshot_2026-02-27_11.55.05.png)

`git push` is used to:

> Upload your local commits to a remote repository (like GitHub).


![git](images/day5/Screenshot_2026-02-27_12.13.37.png)
![git](images/day5/Screenshot_2026-02-27_11.34.48.png)



# 🌍 What is GitHub?

GitHub is a **cloud platform that hosts Git repositories**.

It is used to:

- Store repositories online
    
- Collaborate with teams
    
- Manage pull requests
    
- Run CI/CD
    
- Review code


##  DAY 6
# What Is a Branch in Git?

A **branch** is:

> 🧠 A separate line of development in your project.

It allows you to:

- Work on new features
    
- Fix bugs

![git](images/day6/Screenshot_2026-02-28_12.21.09.png)
git switch -c testing
![git](images/day6/Screenshot_2026-02-28_12.22.55.png)
![git](images/day6/Screenshot_2026-02-28_12.27.18.png)


![git](images/day6/Screenshot_2026-02-28_12.28.44.png)
- You are on the **testing** branch.
    
- You added a new file `git.txt`.
    
- You committed it with message `"new file"`.
    
- You pushed it to GitHub using `git push -u origin testing`.
    
- Now your local branch is connected to GitHub and everything is up to date. 

![git](images/day6/Screenshot_2026-02-28_12.33.59.png)
![git](images/day6/Screenshot_2026-02-28_12.34.39.png)
![git](images/day6/Screenshot_2026-02-28_12.39.20.png)

![git](images/day6/Screenshot_2026-02-28_12.39.51.png)


![git](images/day6/Screenshot_2026-02-28_12.48.47.png)
![git](images/day6/Screenshot_2026-02-28_12.49.49.png)
git branch -r      # Shows remote branches (branches on GitHub)

origin/HEAD -> origin/main   # Default branch on remote is main
origin/main                 # Remote main branch
origin/testing              # Remote testing branch

![git](images/day6/Screenshot_2026-02-28_13.13.20.png)

![git](images/day6/Screenshot_2026-02-28_14.28.53.png)
### What is **Git Stash**?

**Git stash** is used to temporarily save your uncommitted changes  
so you can switch branches without committing them.

![git](images/day6/Screenshot_2026-02-28_14.57.28.png)


![git](images/day6/Screenshot_2026-02-28_15.00.49.png)
### What is `git stash pop`?

**`git stash pop`** is used to:

> Bring back your saved (stashed) changes  
>  And remove them from the stash list
![git](images/day6/Screenshot_2026-02-28_15.01.31.png)
### What is **Git Merge**?

**Merge** means:

>  Combine one branch into another branch.

