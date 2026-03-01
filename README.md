# Jesse Noppe

**Backend & AI Engineer building production-grade systems with a focus
on retrieval-augmented generation, scalable cloud architecture, and
responsible machine learning.**

M.S. Computer Science --- NYU Tandon (Dec 2025) --- GPA: 3.73

I design and ship intelligent systems end-to-end: from distributed data
pipelines and database design to AI orchestration, evaluation, and
deployment.

------------------------------------------------------------------------

## What I Build

-   Multi-tenant AI-backed applications\
-   Retrieval-Augmented Generation (RAG) systems\
-   Serverless and microservice-based architectures on AWS\
-   Fairness and robustness evaluations for ML systems\
-   Distributed data workflows with Spark\
-   Systems-level tooling in C

------------------------------------------------------------------------

# Featured Projects

## Pack

Production AI-powered family archive platform\
**Stack:** FastAPI · Next.js · TypeScript · MongoDB · AWS S3 · Clerk ·
OpenAI · Vercel

GitHub: https://github.com/jessenb16/Pack
Live: https://pack-wine.vercel.app/

Built a secure, multi-tenant archive system where families can store
important documents and memories. Integrated an AI agent that retrieves
documents or answers questions using vector search and RAG.

**Key engineering components:** - Multi-tenant architecture with secure
authentication (Clerk) - PDF text extraction + GPT-4o Vision
transcription pipeline - Embedding generation and MongoDB vector
search - Tool-using AI agent with guardrails to prevent rigid or unsafe
behavior - AWS S3 for document storage - Lightsail + Vercel deployment -
CI/CD via GitHub Actions

**Hardest challenges:** - Designing AI tool usage flows that remain
flexible but avoid hallucinated operations - Ensuring strong security
guarantees without introducing high latency - Structuring embeddings and
retrieval for accuracy and responsiveness

Full ownership: architecture, backend, frontend, AI integration,
deployment.

------------------------------------------------------------------------

## Coding Interviewer

AI-driven technical interview practice platform\
**Stack:** React · AWS Lambda · Cognito · API Gateway · RDS (PostgreSQL)
· ECS Fargate · SQS · OpenAI

GitHub: https://github.com/mr2447/coding_interviewer
Live: https://d218nvq550m5aj.cloudfront.net/

Built in a team of four. Designed a scalable, microservice-forward
architecture that:

-   Selects coding questions based on user history\
-   Generates in-context hints based on current code\
-   Enforces guardrails to ensure AI selects valid problems

**My contributions:** - Designed full system architecture and
infrastructure diagram\
- Database schema design and index optimization\
- Wrote optimized SQL queries to support AI-driven question selection\
- Implemented Lambda-based AI orchestration flow\
- Helped shape UI/UX for structured practice sessions

**Key engineering tradeoffs:** - Cold-start latency vs. serverless
scalability\
- Guardrails for AI validity vs. system flexibility\
- Coordinating infrastructure across Lambda, ECS, RDS, and SQS

------------------------------------------------------------------------

## NYC Fire Risk Predictor

Distributed data + ML analysis at scale\
**Stack:** PySpark · Scikit-Learn

GitHub: https://github.com/Vialor/NYU-Big-Data-Final-Project

Tested the hypothesis that heating complaints predict increased fire
risk in NYC buildings.

-   Processed 26+ million records from NYC Open Data\
-   Joined 311 complaint data with fire incident data\
-   Structured temporal experiments (2-month window prediction)\
-   Built ML models and visualized prediction heatmaps

**Major technical challenge:** Fire data was not building-level, while
311 data was. Solved via: - Geocoding + spatial grouping into NYC
regions\
- Asynchronous API calls with semaphore-limited concurrency\
- Reduced processing time by \~90%

------------------------------------------------------------------------

## Responsible AI Audit --- Santander Product Recommendation ADS

**Stack:** Fairlearn · SHAP · Scikit-Learn

GitHub: https://github.com/jessenb16/Responsible-AI-Final-Project

Technical audit of an automated banking product recommendation system
based on the Kaggle Santander challenge.

**Focus:** - Performance evaluation (MAP@7, Precision@7, Recall@7)\
- Gender-based fairness analysis\
- Demographic parity difference & selection rate\
- Feature attribution via SHAP

**Findings:** - Higher performance for female customers\
- Demographic parity disparities for certain financial products\
- Gender was a significant explanatory feature, with limited proxy
correlations

------------------------------------------------------------------------

## Deep Learning Research

### CIFAR-10 Classification (ResNet under 5M parameters)

Achieved 96.69% test accuracy through systematic architecture and
hyperparameter optimization.

### Parameter-Efficient Fine-Tuning with LoRA (RoBERTa-base)

Fine-tuned under a strict 1M parameter budget for AGNEWS classification.
Achieved 91.41% validation accuracy in 1200 steps.

### Adversarial Attacks on ResNet-34

Evaluated FGSM, PGD, and patch-based PGD attacks. Demonstrated strong
architecture-dependent robustness differences.

------------------------------------------------------------------------

## Systems Work

### xv6 Strace Implementation

**Stack:** C · Docker

Added system call tracing functionality to xv6 by modifying syscall and
process handling logic while preserving system integrity.

------------------------------------------------------------------------

# Technical Stack

**Languages**\
Python · C++ · C · SQL · TypeScript · JavaScript · Julia

**Backend & Frameworks**\
FastAPI · Django · Flask · Next.js · React

**Databases & Data**\
PostgreSQL · MongoDB · MySQL · Apache Spark · Kafka · Hadoop

**Cloud & DevOps**\
AWS · Docker · Kubernetes · GitHub Actions · UNIX/Linux

**AI & ML**\
PyTorch · Scikit-Learn · OpenAI API · RAG · LangChain · LangGraph ·
Fairlearn · SHAP · Virny

------------------------------------------------------------------------

# What I Care About

-   Building AI systems that operate reliably in production\
-   Designing data flows that scale\
-   Evaluating ML systems for fairness and robustness\
-   Making thoughtful architectural tradeoffs instead of chasing trends

------------------------------------------------------------------------

📫 jn2934@nyu.edu\
📍 New York
