---
# NOTE: Values in this frontmatter flow into a <script type="application/ld+json">
# block in templates/site.html. Pandoc HTML-escapes them by default, so the
# JSON would be invalid for any value containing ", &, <, >, or \. Keep all
# values JSON-safe (alphanumeric + standard URL chars + spaces + safe punctuation).
title: "Paweł Jacek Frąckowiak — Software Architect / Kubstronaut"
author: "Paweł Jacek Frąckowiak"
description: "Hands-on Software Architect and Kubstronaut with deep infrastructure expertise (Kubernetes, Go, Security) and practical application development (Python, GenAI)."
subject: "CV / Resume"
keywords:
  - Software Architect
  - Kubernetes
  - Go
  - Python
  - GenAI
  - Security
  - Platform Engineering
lang: en
url: https://pfrack.github.io/
---

# Paweł Jacek Frąckowiak

Software Architect and Kubstronaut, currently leading AI platform work at Capgemini.

Wrocław, Poland · [pawelfrackowiak@protonmail.com](mailto:pawelfrackowiak@protonmail.com) · [LinkedIn](https://linkedin.com/in/pawelfrackowiak) · [GitHub](https://github.com/pfrack) · [PDF](files/cv.pdf)

## Professional Summary

Hands-on Software Architect and Kubstronaut with a strong foundation in Quality Assurance and Automation. I combine deep infrastructure expertise (Kubernetes, Go, Security) with practical application development (Python, GenAI). I focus on moving AI projects from "proof of concept" to stable, scalable production systems. My goal is to engineer reliable platforms where code quality and operational security are priorities, not afterthoughts.

## Experience

**Architect (Go, Python, GenAI) / Lead Developer *(Managing Solution Architect)*** *Capgemini Polska Sp. z o.o., Wrocław, Mar 2022 -- Present*

- **SmartDesk (Document Intelligence):** Architected the on-premise infrastructure for an AI-driven data extraction platform processing complex documents (leases, resumes, certificates). Designed a hardware-aware pipeline using Docling (FastAPI) that toggles between CPU-bound **PaddleOCR** and GPU-bound **dots.mocr** based on hardware availability. Configured the BiFrost LLM gateway to dynamically route standard LLM requests to **Gemma 4** (served via vLLM) and specialized OCR workloads to the OCR model. Bridged the AI backend with a React/NestJS frontend, ensuring seamless operation across AWS cloud and secure bare-metal environments.
- **Multi-Agent Architecture Consulting (Azure):** Acted as a Consulting Architect advising enterprise clients on the adoption of advanced AI patterns using the Microsoft Agentic Framework. Consulted on the strategic implementation of an "Agent Mesh" architecture, demonstrating how a central orchestrator/planner agent can dynamically route tasks to specialized containerized agents via skill registration. Guided the client's integration strategy for leveraging Model Context Protocol (MCP) to autonomously execute complex workflows within **SAP** and **ServiceNow (SNow)** environments.
- **GenAI Platform Architecture:** Architected a RAG-as-a-Service platform enabling employees to upload documents and interact conversationally. Designed end-to-end document pipeline using Unstructured AI (chunking), Azure AI Search, SharePoint, S3 buckets, DynamoDB, Lambda, Step Functions, SQS/SNS, EC2 instances, and API Gateway for secure self-service document processing.
- **Kagent Research (DevOps AI):** Conducted in-depth research and proof-of-concept development for Kagent – an AI agent framework specifically designed for DevOps workflows. Evaluated agentic patterns for automating infrastructure provisioning, CI/CD pipeline optimization, and Kubernetes cluster management using advanced LLM orchestration techniques.
- **High-Performance Backend (Go):** Tech Lead for the *Digital Euro* integration layer. Engineered a secure, low-latency system integrating HSM, caching strategies, DESP Interface, and Kubernetes to handle financial transaction standards.
- **GenAI Strategy & Consulting:** Acting Architect in the GenAI Expert Center, advising projects on "Build vs. Buy" strategies. Evaluated when to deploy custom private models (vLLM, Ollama) versus leveraging existing internal company assets or cloud APIs, balancing security, cost, and compliance.
- **Enterprise Security Integration:** Contributed to the development of a Go-based Key Management System (KMS) for SAP BTP. Implemented critical gRPC/OAuth2 components to enable secure cryptographic operations in a cloud-native environment.
- **Project Leadership & Mentoring:** Led dynamic project-based engineering teams across Go/Python streams. Managed recruitment processes and guided the strategic migration from legacy RPA to modern Power Platform architectures.
- **Specialized Domain Applications:** Developed critical tools for clients, including a nuclear waste calculation engine (Python/Pandas) and productivity add-ins (TypeScript/Node.js) for the MS Office ecosystem.

**Architect (Go, RPA) / Lead Developer *(Senior App. Consultant)*** *Capgemini Polska Sp. z o.o., Wrocław, Jan 2020 -- Mar 2022*

- **Go Ecosystem Pioneer:** Spearheaded the first commercial Golang initiative in the Wrocław branch. Architected the core development ecosystem from ground zero, delivering critical tooling (OpenAPI transpilers) and a containerized test framework (Resty, Godog), effectively proving Go's viability for enterprise delivery.
- **Intelligent Automation & DevOps:** Tech Lead for the RPA Center of Excellence. Pioneered the use of **Jenkins as a Robot Orchestrator** and integrated UiPath with AI systems for a "Level 1.5 Support" platform, bridging classic RPA with CI/CD practices.
- **Process Intelligence:** Supported business optimization initiatives using Process Mining tools (Celonis, Qlik) to identify automation bottlenecks and validate solution designs (SDD/PDD) with real data.
- **Custom Integration Modules:** Developed advanced UiPath activities in C# (WPF) to bridge automation gaps, enabling secure SSH connections, advanced text parsing, and high-performance API integrations unavailable in standard libraries.
- **Technical Recruitment & Mentoring:** Acted as the primary technical recruiter and mentor for a 12-member team, defining coding standards and training the first wave of developers in the new tech stack.

**Lead Automation Engineer *(Senior Test Consultant)*** *Capgemini Polska Sp. z o.o., Wrocław, Jan 2019 -- Jun 2020*

- **Framework Development (Selenium):** Designed and maintained a custom Java-based Selenium automation framework (JUnit 5), establishing reusable test patterns and stable execution pipelines.
- **Automation Strategy:** Defined and executed the test automation approach across teams, improving test coverage and reliability of regression runs.
- **Performance Engineering:** Conducted performance analysis and load testing to identify system bottlenecks and provide actionable recommendations.

**Technical Trainer (Python & Selenium)** *Testuj.pl, Dec 2018 -- Apr 2019*

- **Expert Training Lead:** Conducted specialized weekend workshops and corporate training sessions on Test Automation using Python and Selenium WebDriver.
- **Curriculum Development:** Designed practical coding exercises and training materials to upskill professional QA engineers.

**Lead Automation Engineer (Embedded Web) *(Senior Test Engineer)*** *Silicon & Software Systems Polska Sp. z o.o., Wrocław, Dec 2015 -- Dec 2018*

- **Scale & Reliability:** Managed a daily execution pipeline of ~4,000 tests, combining high-level GUI validation with low-level embedded verification.
- **Hybrid Framework Architecture:** Architected a dual-layer automation ecosystem: a Java/Selenium framework for web interfaces and Python-based scripting for direct embedded device testing and hardware interaction.
- **Technical Leadership:** Led the comprehensive testing strategy for complex embedded systems, bridging the gap between hardware and software QA.

**Software Test Engineer** *Fara Polska Sp. z o.o., Warsaw, Nov 2013 -- Nov 2015*

- **System Validation:** Coordinated end-to-end acceptance testing for public transport ticketing systems, ensuring compliance with critical SLAs and reliability standards.

**R&D Specialist / Test Engineer** *Telekomunikacja Polska S.A. (Orange Labs), Jun 2009 -- Oct 2013*

- **Lab Automation & R&D:** Automated hardware/software testing workflows for telecommunication systems, reducing cycle time by ~30%. Managed laboratory infrastructure and executed complex test protocols.

## Education

**Postgraduate Studies in E-Business** *Warsaw University of Technology, Poland, 2010*

- Focus: E-business strategies, internet technologies, and digital commerce models.

**M.Sc. Eng. in Electronics and Telecommunications** *Poznań University of Technology, Poland, 2008*

- Specialization: Information Transport Networks
- Thesis: "P2P in 4G Mobile Networks" (Radio Communication Dept.). Developed a C++ simulation of the MAC Layer P2P mode for the WINNER system, focusing on network performance analysis.

## Key Certifications & Awards

- **Kubernetes Ecosystem (Kubstronaut):** CKS (10/2025), KCSA (11/2025), CKAD (07/2025), CKA (12/2024), KCNA (08/2025). Awarded the **Kubstronaut** title for holding all 5 CNCF certifications simultaneously.
- **Cloud & Architecture:** Google Cloud Professional Cloud Architect (12/2023), Capgemini Certified Architect (02/2022)
- **Other:** UiPath RPA Developer Advanced (11/2019), ISTQB Advanced Level Technical Test Analyst (10/2014), ITIL Foundation (10/2021)

## Technical Skills

- **Core Languages:** Golang, Python, Bash/Shell Scripting
- **Cloud Native & DevOps:** Kubernetes (Kubstronaut), Docker, Helm, Terraform, Ansible, AWS (Lambda, ECS, DynamoDB), Azure AI, Google Cloud (GCP), CI/CD (Jenkins, GitHub Actions), Linux Administration
- **AI & LLM Engineering:** LangChain, vLLM, Ollama, Hugging Face, LocalAI, RAG Architectures, Vector Databases, BiFrost, Docling, PaddleOCR, dots.mocr, Microsoft Agentic Framework, MCP
- **Backend & Integration:** FastAPI, gRPC, REST API Design, OpenAPI/Swagger, AsyncAPI, OAuth2, HSM Integration, NestJS, React
- **Automation & Quality:** Pytest, Go Testify, Godog, Performance Testing, Integration Testing
- **Leadership:** Technical Team Leadership, Solution Architecture, Mentoring, Agile/Scrum, Recruitment
- **Prior Engineering Focus:** C++, Java, C#, Selenium WebDriver, UiPath (RPA), Process Mining (Celonis)

## Languages

**Polish**: Native | **English**: Advanced (C1/C2) | **German**: Intermediate

Last updated: 2026-06
