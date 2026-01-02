# SRE Challenge - Programming Test

This repository contains the base for the Site Reliability Engineering (SRE) challenge at Nsx.

## Prerequisites

To run the challenge locally, you must have the following items installed on your machine:

* A programming language: **Golang** or **Python** — pick the one you're most comfortable with  
* Docker (or another compatible container runtime)  
* Git  
* A code editor of your choice  

**⚠️ Make sure these requirements are installed and working properly before starting the challenge.**

Alternatively, if you can't or prefer not to install the prerequisites locally, this repository is already set up to run via GitHub Codespaces.

## Using the Devcontainer

The repository includes a `.devcontainer/` folder, which defines a pre-configured development environment. You can use this environment either locally (with Dev Containers support in VS Code, for example) or directly in Codespaces.

If you don’t yet have access to a Codespace, we can provide a link to open this repository in a ready-to-use environment without needing to configure anything locally.

## 🧠 What to Expect and What We’re Looking For

On the day of the interview, you’ll be given a live, hands-on challenge involving **programming, containers, and a Linux environment**.

You will be asked to solve a realistic problem based on a scenario presented at the time. The goal is for you to use **programming logic** and basic system tools to automate the collection and interpretation of relevant environment data.

> **Important:** The goal is not to get everything perfect — we want to understand **how you think, investigate, and solve real-world production problems.**

## ✅ What Will Be Evaluated

During the challenge, we will observe:

- 🧩 Your ability to **understand and break down a problem**
- 💻 Use of programming to automate tasks (Python or Go)
- 🔍 Ability to **investigate** the state of the system and containers
- 🌐 Independence in researching tools/libraries
- 🧼 Clarity, organization, and overall quality of your code
- 🔄 Your reasoning on how the solution could evolve (scalability, extensibility)

## 📌 Expected Requirements

We expect you to:

- Be familiar with **Linux and Docker-based environments**
- Know how to use **basic system commands** and **inspect container status**
- Be able to write a simple script or app that reads information and returns a **structured output**
- Use structured programming, even if simple, to build your solution
- Research and use libraries as needed, explaining your choices
- Use a Docker library to interact with containers programmatically (e.g., `docker` for Python or `github.com/docker/docker/client` for Go)

## 🏗️ Infrastructure Challenge (Second Round)

If you advance to the second round, you'll participate in an **infrastructure-focused discussion and challenge** where we'll dive deep into:

### Core Topics

- **Cloud Infrastructure**: AWS, GCP, Azure architectures and best practices
- **Infrastructure as Code (IaC)**: Terraform, CloudFormation, Pulumi
- **GitOps**: Infrastructure deployment and management through Git workflows
- **Kubernetes**: Container orchestration, deployments, services, and cluster management
- **CI/CD**: Pipeline design, automation, and deployment strategies

### Key SRE Concepts

We'll discuss essential reliability engineering concepts and practices:

- **Observability**: Monitoring, logging, tracing, and alerting (Prometheus, Grafana, ELK stack)
- **Reliability Engineering**: SLIs, SLOs, SLAs, and error budgets
- **Incident Management**: On-call practices, runbooks, postmortems
- **Capacity Planning**: Resource management, scaling strategies, cost optimization
- **Security & Compliance**: Infrastructure security, secrets management, compliance as code
- **Disaster Recovery**: Backup strategies, failover mechanisms, RTO/RPO objectives
- **Performance**: Load testing, optimization, and tuning
- **Configuration Management**: Service discovery, feature flags, dynamic configuration

### What We're Looking For

During this round, we want to understand:

- Your experience designing and managing production infrastructure
- How you approach infrastructure challenges and trade-offs
- Your knowledge of modern DevOps/SRE tooling and practices
- Ability to architect scalable, reliable, and maintainable systems
- Understanding of operational excellence and production readiness

> **Note:** This may include a practical exercise involving infrastructure design, troubleshooting, or implementing IaC solutions