# Jerry Xie
**Senior Backend Engineer**

linkedin.com/in/chenxie-aa8266135 | cxiejobs@gmail.com | github.com/cxiesde-art | +1 4124827842

## Professional Experience

### Snorkel AI | Jan 2026 - Present
**Backend Tech Stack: Python, Docker, Agent Frameworks**
- Contribute to **Terminus Bench**, an open-source coding-agent evaluation benchmark that packages repository tasks in sandboxed environments for safe execution and testing across agent frameworks.
- Design coding-agent evaluation projects from task definition through execution and scoring, expanding benchmark coverage and improving assessment reliability across different agent frameworks.
- Develop the **CyberSWE** security benchmark by seeding application-layer vulnerabilities in production repositories, writing symptom-only prompts, implementing hidden black-box tests, and building deterministic Docker environments; validate reference fixes through Harbor/Realm oracle workflows.

### Weibo | Senior Backend Engineer | Oct 2024 - Jan 2026
**Backend Tech Stack: Python, Go, FastAPI, Gin, REST APIs**
**AI Stack: PyTorch, vLLM, vLLM-Ascend, Verl, Qwen, RAG**
- Built a DeepResearch-style report-generation system with four cooperating agents: a planner decomposes questions, a researcher performs multi-turn retrieval and source synthesis, a verifier checks claims against evidence, and a writer drafts and iteratively refines reports.
- Designed the agents’ request and response protocol, passing structured sub-queries and evidence cards between planner and researcher; claim-level citation checks and revision loops connected verifier feedback to report updates.
- Built a Qwen-based RAG assistant with short-term session memory and long-term vector-store memory, grounding multi-turn answers in a curated knowledge base through retrieval-augmented prompts and context windowing.
- Led backend architecture for a multi-turn dialogue system and built a user-profiling recommendation module for follow-up questions; applied SFT and DPO to high-quality conversational data, improving dialogue quality, transition rate, and CTR.
- Trained a Search-R1-style search agent that interleaves reasoning with generated search calls; set up live-retrieval rollouts, verifiable final-answer rewards, and policy updates that improved multi-hop question answering over prompt-only baselines.
- Designed structured reasoning outputs for search and decision-making, and implemented a modular pipeline with swappable language models and search backends to improve retrieval efficiency and answer quality.
- Built and optimized vLLM inference deployments on NVIDIA and AMD GPUs and worked with vLLM-Ascend for heterogeneous accelerator serving; deployed quantized models and tuned configurations for GPU memory use, throughput, and low-latency inference.
- Enabled vLLM prefix caching for shared prompts and reusable context, reducing repeated KV-cache computation and improving time-to-first-token and end-to-end response latency.

<!-- PAGEBREAK -->

### Microsoft | Software Engineer | Dec 2022 - Oct 2024
**Tech Stack: Azure ML, Python, PyTorch, GPT-4o, Llama 3, Mistral**
- Implemented Azure ML Studio fine-tuning pipelines for Llama 3, GPT-4o, Mistral, and other base models, connecting tokenization, preprocessing, verification, prompt-instruction construction, LoRA fine-tuning, deployment, and evaluation; generated pipeline SBOMs as part of delivery.
- Built English and multilingual training-data pipelines for GPT-3.5-turbo and GPT-4 summarization, including Chinese, Korean, and eight additional languages, and evaluated the resulting fine-tuned models end to end.
- Managed training data in Azure Blob Storage through repeatable tokenization, preprocessing, verification, and prompt-instruction stages, organizing source data and model-ready inputs across the fine-tuning workflow.
- Used GPT-4 to augment small training datasets, then evaluated GPT-3.5-turbo and Llama 3 fine-tunes on Microsoft Teams meeting summaries to assess the effect of the added data.

### Kafang Tech | Software Engineer | Sep 2019 - May 2021
**Backend Tech Stack: Go, C++, Kubernetes, REST APIs, gRPC, Redis, Prometheus, Alertmanager, Grafana**
- Designed a cloud-native ML training platform deployed across two Kubernetes clusters, defining user authentication and a sidecar/gateway topology that separated frontend requests from training-job execution.
- Built 10+ Go REST APIs for training-data upload, validation, and management, supporting frontend workflows and the platform’s core data lifecycle.
- Implemented Redis caching that reduced data retrieval time by 60%; added a Redis task queue to decouple sidecar and gateway work for training jobs, with gRPC communication between gateway and queue services.
- Built Go/C++ microservices, integrated backend services with Kubernetes deployments and a Vue.js frontend, and developed a Go email-notification module for user-account management.
- Added dynamic memory-alert rules in Prometheus, configured Alertmanager email/Slack routing, and built Grafana dashboards, reducing false alerts from 46.6% to 17.6%.

## Open Source
**Terminus Bench | Coding-Agent Evaluation Benchmark**
Python and Docker benchmark for safely executing and testing AI-generated code. github.com/laudeinstitute/terminal-bench

## Education
**Carnegie Mellon University** | M.S. Computer Engineering, Software Engineering track | Jun 2021 - Dec 2022
**Dalian University of Technology** | B.Eng. Chemical Engineering, Computation track | Sep 2015 - Sep 2019
