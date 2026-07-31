---
title: "Event 3"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.2. </b> "
---

# Summary Report: “FCAJ - Agentic AI Build Week Showcase” 25-07-2026

### Event Objectives

* Recreate the thrilling and competitive atmosphere of the **Agentic AI Build Week** Hackathon.
* Listen to real-world hands-on experience sharing about the 24-hour continuous journey of researching, developing, and troubleshooting (Building, Failing, and Learning) from competing teams.
* Explore innovative application solutions combining **Agentic AI** with the **AWS Cloud** ecosystem to solve real-world problems in business, operations, and governance.
* Learn valuable lessons in Cloud-native architecture design, AI Agent integration, scope management under pressure, and persuasive pitching skills before a panel of judges.

### List of Competing Teams

1. **Team 3KA:** Project **S.H.E.P.H.E.R.D.** (Smart Human-flow Evaluation, Prediction, Hazard Detection, Response, and Dispatch)
   * *Members:* Huynh An Khuong, Nguyen Quoc Huy, Ngo Quang Khoi, Hoang Le Thanh Duc, Dang Nguyen Phuoc Loc, Dang Truong Hung.
2. **Team Plan V:** Project **Solution Architect Professional AI Native App**
   * *Members:* Pham Tien Thuan Phat, Huynh Hoang Long, Le Minh Nghia, Tran Dai Vi, Nguyen An.
3. **Dream AI Team:** Project **Signal Scout**
   * *Members:* Le Tan Luc, Do Hoang Hieu, Trieu Quoc Hao, Nguyen Van Duy Khiem, Nguyen Cong Minh, Nguyen Tran Minh Quan.
4. **One Team (Hackathon Champions):** Project **AI-Powered Conversation Ordering: KFC Bot Agent**
   * *Members:* Anh Duy, Tran Dong, Doan Trung, Minh Viet, Anshul Roy.

### Key Highlights

#### 1. Project S.H.E.P.H.E.R.D. (Team 3KA) — AI Crowd Monitoring & Flow Management

* **Problem Statement:** Current crowd, queue, and traffic monitoring processes at large events are mostly manual, slow to respond, and prone to missing critical incidents.
* **Solution:** An Agentic AI system that automatically analyzes live video camera feeds in real time to measure crowd density, detect early signs of congestion, and trigger proactive alerts for facility operators.
* **AWS & Tech Stack:** Tightly integrates YOLO + ByteTrack, Amazon SageMaker, Amazon Bedrock AgentCore + Strands Agent, and a React Monitoring Dashboard.
* **Agentic AI Layer:** 
  * *Autonomous Monitor:* Continuously tracks crowd metrics and automatically generates early risk alerts.
  * *Operator Copilot:* A natural-language Q&A assistant enabling operators to query real-time conditions and receive immediate action recommendations.  

#### 2. Solution Architect Professional AI Native App (Team Plan V) — AI Assistant for Cloud Architects

* **Problem Statement:** Solves the massive operational burden on Solution Architects who manually read BRD/PRD documents, draw architecture diagrams from scratch, write IaC code (Terraform), and calculate complex cloud estimates.
* **Solution:** An AI-Native application that automatically extracts requirements, proposes standardized Cloud architecture options, generates editable **Draw.io** diagrams featuring official AWS icons, outputs **Terraform (IaC)** code, and calculates directional AWS cost estimates for the `ap-southeast-1` region.
* **AWS & Tech Stack:** AWS CloudFront, Cognito, ALB, ECS Fargate (Backend & Agent), PostgreSQL, Amazon Bedrock model, EFS, ECR, S3 Buckets, and CloudWatch. 

#### 3. Signal Scout (Dream AI Team) — AI Corporate Strategic Change Detection

* **Problem Statement:** Corporate financial and operational data is heavily fragmented; detecting early signals of corporate restructuring or competitive threats requires massive analytical resources.
* **Solution:** An Agentic AI platform that automatically collects, verifies evidence, and analyzes operational metrics to generate risk alert reports for executive strategy and risk management teams.
* **AWS & Tech Stack:** Amazon Bedrock (Tokens), AgentCore Short-Term Memory & Runtime, AWS WAF, Amplify Hosting, DynamoDB, Lambda, API Gateway, S3 Intelligent-Tiering combined with external data scrapers (Apify, TinyFish, LangFuse). 

#### 4. KFC Bot Agent (One Team) — Multi-Channel Conversational AI Ordering

* **Problem Statement:** Eliminates order drop-offs (Loss of Order) caused by forcing messaging users to leave their chat app, download a new app, or register a new account.
* **Solution:** A multi-channel AI Agent enabling direct in-chat ordering (Zalo OA, WhatsApp, Messenger) with the philosophy *"No app download. No account creation. No lost momentum"*.
* **5-Step Agent Workflow:** *Goal* (Understand intent) --> *Plan* (Formulate steps) --> *Tools* (Query business data) --> *Act* (Update cart/apply vouchers) --> *Verify* (Confirm real cart).
* **AWS & Tech Stack:** Ingestion Layer (AWS WAF, API Gateway, SQS), Bedrock AgentCore, DynamoDB, OpenSearch Service (Vector Store & Full-text Search), ElastiCache, and observability via CloudWatch/X-Ray/GuardDuty.
* **Key Metrics:** Cost of **$0.006 per order**, End-to-End latency of **3–5s**, total monthly infrastructure cost of **$88/month**, and **-60% less infrastructure code** by utilizing Managed Services.  

### Key Takeaways

1. **Core Difference Between Chatbots and AI Agents:**
   * Traditional chatbots merely respond with static text, whereas **AI Agents** proactively formulate plans (Planning), execute tools (Tools), and actively modify system database states.
2. **Scope Management Skills:**
   * A universal lesson shared across teams was *"Small, finished work beats big, broken ideas"* — It is far better to ship a fully functional core feature than an overly ambitious, broken system.
3. **Power of Decoupled & Serverless Architectures:**
   * Designing modular systems (*"Design Once | Deploy Everywhere"*) paired with AWS Managed Services (Amazon Bedrock, ECS Fargate, Lambda, DynamoDB) saves significant infrastructure coding effort while optimizing runtime costs.  

### Applying to Work

* **Upgrading AI Features for Healthcare Web App:** Apply the 5-step processing workflow (*Goal --> Plan --> Tools --> Act --> Verify*) to upgrade the medical Chatbot — automatically extracting patient symptoms, checking doctor availability in the AWS RDS Database, and booking appointment slots automatically.
* **Infrastructure Standardization via IaC (Terraform):** Learn from Team Plan V to write Terraform scripts for automating the provisioning of AWS RDS MySQL, S3 Buckets, and VPC networking.
* **Strengthening Security & Observability:** Adopt security architectures combining AWS WAF, IAM Policies, Secrets Manager, and CloudWatch Logging from KFC Bot and Signal Scout to ensure the complete protection of sensitive patient health data.  

### Event Experience

The **Agentic AI Build Week Showcase** provided a genuinely authentic, exciting, and deeply inspiring experience:

#### High-Intensity Practical Experience
* Hearing stories of "dancing under pressure" during the 24-hour hackathon (debugging code at 3 AM, drinking Redbull to pull all-nighters, and relentless team collaboration) made the raw passion of developers truly tangible.  

#### Expanding Horizons in AI & Cloud
* All 4 projects showcased exceptional technical execution, proving the high viability of AI Agents in solving real-world challenges ranging from food ordering, security crowd management, corporate risk analysis, to automating Cloud Architect workflows.  

#### Personal Growth & Motivation
* Realizing that *"Showing up is already half the battle"*. The inspiration from the competing teams instilled confidence in me to actively sign up for future technology hackathons.  

#### Some event photos
![Event Participation Evidence](/images/4-EventParticipated/event-25072026.jpg)  

> **Summary:** The Showcase event was a fantastic learning milestone, enriching my technical knowledge in Agentic AI on AWS Cloud while reinforcing solid architecture design mindsets for my Healthcare Web Application project.