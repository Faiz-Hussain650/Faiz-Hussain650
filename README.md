<a id="top"></a>

<div align="center">

<h1>Hi, I'm Faiz Hussain 👋</h1>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Outfit&weight=600&size=24&duration=2800&pause=900&color=00B4D8&center=true&vCenter=true&width=640&lines=AI+Engineer+%7C+MLOps+Engineer;AWS+Certified+DevOps+Engineer+Professional;LLM+evaluation+%E2%80%A2+RAG+%E2%80%A2+LLM+security;Terraform+%E2%80%A2+Kubernetes+%E2%80%A2+MLflow" alt="Typing SVG" />
</a>

<p>
  <img src="https://img.shields.io/badge/Milan,_Italy-0D1117?style=flat-square&logo=googlemaps&logoColor=00B4D8" alt="Location" />
  <img src="https://img.shields.io/badge/Open_to-EU_AI_%26_MLOps_roles-00B4D8?style=flat-square" alt="Open to EU roles" />
</p>

<p>
  <a href="#about">About</a> •
  <a href="#projects">Projects</a> •
  <a href="#experience">Experience</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#certifications">Certifications</a> •
  <a href="#connect">Connect</a>
</p>

</div>

<hr />

## About

- 🤖 **AI and MLOps Engineer**: I build and run ML and LLM systems end to end, from experiment tracking to serving and deployment
- 💼 2 years as a **DevOps Engineer (Senior Associate)** at **NTT DATA**, running production AWS infrastructure
- 🔐 MSc thesis on **LLM security**: proactive defences against LLM agents, evaluated on 4 open-source models
- 🎓 **MSc in Data Science**, University of Naples Federico II
- ☁️ **3x AWS Certified**, including DevOps Engineer – Professional
- 🗣️ English C1 | Italian A2 (improving)

<hr />

## Projects

| Project | What it does | Key result | Stack |
|---|---|---|---|
| 🛡️ [**TrustGate – LLM Evaluation and Release Gating**](https://github.com/Faiz-Hussain650/Evaluation-Lab-TrustGate) | Scores LLM, RAG and agent systems and returns **ship / investigate / block** via a statistical non-inferiority test; runs as a GitHub Action that fails a PR on a quality regression | Prediction-powered inference matched classical precision with **~50% fewer human labels** (2,000-item simulation); 49 tests | Python, Pydantic, Typer, SQLite, GitHub Actions |
| 💬 [**Multi-Tenant RAG Customer-Support Agent**](https://github.com/Faiz-Hussain650/Multi-Tenant-AI-Customer-Support-Agent-Platform) · [Live demo](https://support-agent-mjo2.onrender.com/docs) | SaaS support agent that answers each tenant only from its own documents; isolation enforced in SQL on every vector query (OWASP LLM08); low-confidence answers escalate to a human | **0 cross-tenant leaks** across 90 concurrent requests from 3 tenants, at 52.6 req/s | Python, FastAPI, PostgreSQL, Docker, GitHub Actions |
| 🔎 [**Kubernetes Log Anomaly Detection – MLOps Pipeline**](https://github.com/Faiz-Hussain650/Kubes-Log-Anomaly-Detection-MLOps-pipeline_Project) | Train → score → monitor pipeline that ranks 11,000 Kubernetes log lines so on-call engineers review the top 50; every run tracked in MLflow | **ROC-AUC 0.88**, precision@50 of 1.00 (synthetic data, in-sample) | Python, scikit-learn, MLflow, GitHub Actions |
| 🎓 [**MSc Thesis – Proactive Defences Against LLM Agents**](https://github.com/Faiz-Hussain650/Thesis) | Reproduced Cloak, Honey, Trap (USENIX Security 2025) and extended it to 4 locally hosted 4-bit LLMs on 285 MMLU questions | Honeytoken detection **100%** on every model; Trap DSR 23.4% on Llama-3.2-1B vs 3.9% on Mistral-7B | Python, Pandas, Ollama |

<hr />

## Experience

**💼 DevOps Engineer (Senior Associate, IT) | NTT DATA** | Bangalore, India | Sep 2021 – Aug 2023

- Built and managed production AWS infrastructure (EC2, ECS, VPC, S3) with load balancing and auto-scaling
- Automated infrastructure provisioning with **Terraform**, increasing deployment speed by **45%**
- Developed CI/CD pipelines in **Jenkins** and **AWS CodePipeline**, cutting release time from hours to minutes
- Deployed and maintained containerised microservices on **Kubernetes (EKS)** with Docker and Helm
- Configured **CloudWatch** monitoring, logging and alerting; reduced AWS costs by **20%** through right-sizing

<hr />

## Tech Stack

| Area | Tools |
|---|---|
| **Cloud** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=FF9900) ![EKS](https://img.shields.io/badge/EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white) ![ECS](https://img.shields.io/badge/ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white) ![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white) ![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white) |
| **MLOps / LLMOps** | ![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white) |
| **IaC and Containers** | ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white) ![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) |
| **CI/CD and Monitoring** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white) ![CodePipeline](https://img.shields.io/badge/CodePipeline-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white) ![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=for-the-badge&logo=amazoncloudwatch&logoColor=white) |
| **Code, ML and Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) |

<hr />

## Certifications

<p>
  <img src="https://img.shields.io/badge/AWS_Certified-DevOps_Engineer_Professional-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS DevOps Engineer Professional" />
  <img src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect_Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Solutions Architect Associate" />
  <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Cloud Practitioner" />
</p>

<hr />

## Connect

<div align="center">

<a href="https://www.linkedin.com/in/faiz-hussain" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="mailto:faizhussain325@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
&nbsp;
<a href="https://faiz-hussain.vercel.app/" target="_blank">
  <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
</a>

<p><a href="#top">⬆ Back to top</a></p>

</div>
