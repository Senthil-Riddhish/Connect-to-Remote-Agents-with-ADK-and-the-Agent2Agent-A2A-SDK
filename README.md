# 🚀 AI Multi-Agent System using ADK & Agent2Agent (A2A)

This project demonstrates how to build, deploy, and orchestrate **collaborative AI agents** using the Agent Development Kit (ADK) and the Agent-to-Agent (A2A) protocol on Google Cloud.

Instead of isolated AI tools, this system enables **AI agents to discover, communicate, and collaborate remotely**, making it suitable for real enterprise environments.

---

## 📌 Overview

Modern organizations are moving towards **agentic and AI-first architectures**. However, most GenAI systems today are siloed, difficult to maintain, and hard to scale across teams.

This project solves that challenge by implementing:

✔️ Standardized communication between AI agents  
✔️ Remote collaboration across services  
✔️ Centralized agent deployment  
✔️ Secure and scalable architecture  
✔️ Enterprise-ready cloud-native design  

---

## 🧠 What I Built

This project includes:

### 1️⃣ Illustration Agent  
An AI agent that generates branded illustrations based on company guidelines such as:
- Corporate Memphis style  
- Specific color palette  
- Domain-specific imagery  
- Consistent brand tone  

It uses Gemini models and uploads generated assets to Cloud Storage.

---

### 2️⃣ Slide Content Agent  
A second AI agent that:
- Generates slide headlines and body content  
- Dynamically calls the remote illustration agent  
- Produces complete slide-ready output  

This demonstrates **true multi-agent orchestration**.

---

## ⚡ Key Features

🔹 Agent-to-Agent (A2A) communication  
🔹 JSON-RPC standardized protocol  
🔹 Agent discovery via Agent Cards  
🔹 Remote agent invocation  
🔹 Modular and reusable AI services  
🔹 Cloud-native deployment  
🔹 Enterprise scalability  
🔹 Separation of responsibilities  
🔹 Secure and maintainable architecture  

---


This architecture ensures:
- Centralized AI services  
- Reusable enterprise workflows  
- Reduced duplication  
- Scalable agent ecosystems  

---

## 🛠️ Tech Stack

- ADK (Agent Development Kit)  
- Agent2Agent (A2A) SDK  
- Gemini Models  
- Vertex AI  
- Cloud Run  
- Cloud Storage  
- JSON-RPC  
- Python  

---

## 🌍 Why This Matters

Multi-agent AI systems represent the next phase of enterprise AI:

✔️ Autonomous workflows  
✔️ Modular intelligent systems  
✔️ AI collaboration across teams  
✔️ Real-time decision-making  
✔️ Faster innovation cycles  

This approach is already relevant in:
- Enterprise automation  
- Design pipelines  
- Marketing AI  
- Knowledge systems  
- Intelligent assistants  
- Autonomous operations  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.9+  
- Google Cloud account  
- Vertex AI enabled  
- Cloud Run enabled  

---

### Installation

```bash
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo
pip install -r requirements.txt
```

## 🏗️ Architecture
Environment Setup

Create a .env file:
```bash
GOOGLE_GENAI_USE_VERTEXAI=TRUE
GOOGLE_CLOUD_PROJECT=your_project
GOOGLE_CLOUD_LOCATION=global
MODEL=gemini-2.5-flash
IMAGE_MODEL=gemini-2.5-flash-image
```

Deploy to Cloud Run
```bash
adk deploy cloud_run --a2a illustration_agent
```

📊 Future Improvements

Authentication & secure agent communication

Streaming and asynchronous workflows

Observability and monitoring

Multi-cloud support

Integration with ERP and enterprise systems

Advanced multi-agent orchestration

Workflow automation

🎯 Use Cases

🏢 Enterprise knowledge agents
🏢 Automated design and content pipelines
🏢 Customer support automation
🏢 Autonomous AI workflows
🏢 Internal productivity platforms
