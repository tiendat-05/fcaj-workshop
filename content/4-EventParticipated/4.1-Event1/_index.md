---
title: "Event 1"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Summary Report: Event Meet Up 06-06-2026

### Event Objectives

* Share practical career development paths from IT Helpdesk to Senior Sysadmin, Cloud, and DevOps Mindset.
* Update on industry-leading technology trends: GenAI with GraphRAG (Amazon Bedrock & Neptune) and AI-driven Security NIDS combined with AWS WAF.
* Equip methodology on soft skills, effective teamwork, and project management using digital tools.
* Dive deep into hands-on technical solutions on AWS Cloud infrastructure: Real-time Multiplayer Gaming via WebSocket/Lambda and Docker Containerization.

### Speakers

1. **Tran Trung Vinh** - System Administrator at Central Retail Group.
2. **Viet Phat** - AI Major, Swinburne University of Technology.
3. **Truong Huy Phuoc** - Presenter / Teamwork & Collaboration Specialist.
4. **Nguyen Quoc Bao** - Speaker, Cloud & Game Developer.
5. **Le Hoang Gia Dai** - AWS G3 Team, HUTECH University.
6. **Bao Huynh** - Junior Cloud Native Developer at Endava Vietnam, Head of ITea Lab.

### Key Highlights

#### Session 1: From IT Helpdesk to Senior Sysadmin (Speaker: Tran Trung Vinh)

* **Career Development Roadmap:** Transitioning from fundamental end-user support (Helpdesk), shifting mindset toward understanding system architecture (Sysadmin), and adopting modern DevOps practices (Linux, Networking, IaC Terraform, CI/CD, Containers).
* **Operational Mindset:** *Prevent first — fix later*, write process documentation (Runbooks), automate repetitive tasks, and strictly adhere to the rule *"Never test in production"*.  

#### Session 2: Build GraphRAG Applications using Amazon Bedrock and Amazon Neptune (Speaker: Viet Phat)

* **Addressing Traditional RAG Limitations:** Standard Vector Search-based RAG struggles with complex multi-step reasoning (Multi-hop Reasoning).
* **GraphRAG Solution:** Integrating Knowledge Graphs to explicitly represent and capture relationships between entities.
* **AWS Deployment Strategies:** Leveraging either the *Fully Managed Route* (Amazon Bedrock Knowledge Bases + Amazon Neptune Analytics) or the *Custom Route* (LlamaIndex + Amazon Neptune) for flexible relationship queries.

#### Session 3: The Art of Effective Teamwork (Speaker: Truong Huy Phuoc)

* **The 4 Golden Rules:**
  1. *Clear & Shared Goals:* Transparent collective objectives.
  2. *Right Person, Right Place:* Assigning tasks based on individual strengths.
  3. *Open Communication & Active Listening:* Transparent dialogue and proactive listening.
  4. *Personal Accountability:* End-to-end personal responsibility for assigned work.
* **Digital Tools Adoption:** Task management with Trello/ClickUp, documentation via Google Workspace, and team communication via Slack/Discord. 

#### Session 4: Connecting Godot Clients with AWS WebSockets (Speaker: Nguyen Quoc Bao)

* **Serverless Multiplayer Architecture:** Utilizing API Gateway WebSocket for full-duplex real-time connections, AWS Lambda (Node.js) for matchmaking, and DynamoDB for session state persistence.
* **Client Integration:** Integrating `WebSocketPeer` in Godot 4 to parse real-time JSON payloads.
* **Challenges & Solutions:** Handling stale connection drops, optimizing DynamoDB Scan costs, and evaluating transitions to AWS GameLift for complex FPS/Action games.  

#### Session 5: Machine Learning-based NIDS on AWS (Speaker: Le Hoang Gia Dai)

* **Overcoming Traditional WAF Barriers:** Rule-based security in WAF is insufficient against modern Zero-day threats.
* **ML NIDS Integration:** Training intrusion detection models using the CSE-CIC-IDS2018 dataset. Test evaluations using the **LightGBM** algorithm achieved **95.86%** accuracy.
* **Comprehensive Cloud Architecture:** Combining WAF, ALB, EC2, Kinesis, Lambda, Security Hub, and CloudWatch into an automated threat detection and response pipeline. 

#### Session 6: Docker – A Containerization Technology (Speaker: Bao Huynh)

* **Virtualization vs Containerization:** Comparing heavy Virtual Machines (VMs) with lightweight, instant-booting, and resource-efficient Docker Containers.
* **Docker Fundamentals:** Understanding layered image architecture in Dockerfiles, layer caching mechanisms, and the *"Build once, run anywhere"* philosophy.
* **Practical Applications:** Standardizing Dev/Test environments, developing microservices, and supporting CI/CD pipelines. 

### Key Takeaways

#### Technical Mindset

* Master strong fundamentals (Linux, Networking, Docker) before advancing to complex technologies like Cloud, DevOps, or AI.
* Learn to combine various AWS Cloud services (Cognito, RDS, Lambda, SageMaker, WAF, S3) into cohesive solutions rather than viewing them as isolated tools.
* Adopt a proactive security mindset and adhere to safe operational principles (Preventive Care, Never test in prod).  

#### Soft Skills & Management

* Understand group project operations through the 4 Golden Rules and fully utilize digital tools (Trello, Discord, GitHub) to track progress.
* Recognize the immense value of real-world hands-on projects (Real Portfolios) to employers compared to solely pursuing theoretical certifications.  

### Applications to Internship Project

1. **Infrastructure & Environment Standardization:** Containerize the entire web application (NestJS Backend & Next.js Frontend) using **Docker** for consistent execution from Local environments to AWS Cloud (ECS/EC2).
2. **AI & WebSocket Feature Upgrades:**  
   * Implement a **WebSocket Gateway** to build a real-time medical triage chatbot.
   * Explore **GraphRAG** principles to optimize relationship mapping between *Symptoms --> Specialties --> Doctors*.
3. **Enhanced Security & Monitoring:** Configure **AWS WAF**, apply Middleware Rate-Limiting, anonymize data using UUIDs, and centralize all system logs on **AWS CloudWatch** for real-time anomaly detection.
4. **Team Operational Optimization:** Set up transparent Trello/ClickUp boards for task distribution and write comprehensive Runbooks/Documentation for the Database Schema.ty  

### Event Experience

The sessions delivered a comprehensive and enriching learning experience:
* **High Practical Value:** Speakers shared real-world experiences, genuine production incidents, and daily operational lessons, providing valuable industry insights.
* **Cutting-Edge Trends:** The blend of traditional Cloud infrastructure, Containerization, and advanced AI technologies (GraphRAG, ML NIDS) bridged the gap between academic theory and enterprise practices.
* **Strong Inspiration:** Hearing personal career journeys—from IT Helpdesk to successful Cloud Developers/Sysadmins—reinforced my confidence and motivation to excel in my internship and future engineering endeavors.  

#### Some event photos
![Event Participation Evidence](/images/4-EventParticipated/event-06062026.png)  

> **Summary:** The event served as a significant milestone, enriching my technical knowledge in AWS Cloud, AI, and DevOps while shaping a professional engineering mindset for my career path.
