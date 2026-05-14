# AI Jargon Decoder

Workflow-based AI assistant designed to classify user input and simplify medical terminology into plain English using an n8n automation pipeline.

This project focuses on practical AI workflow orchestration, conditional routing, and prompt-controlled responses rather than custom model training or advanced agent infrastructure.

---

## 🚀 Overview

The workflow processes incoming user messages and routes them through different response paths based on message type.

### Current Behavior

- Medical-related input → simplified explanation flow
- General conversation → friendly assistant response flow

---

## 🛠 Tech Stack

- n8n
- Google Gemini API
- LangChain nodes
- Prompt-based classification logic

---

## 🧩 Architecture

```text
User Input
   ↓
Intent Classification
   ↓
Conditional Routing
   ├── Medical Simplification Flow
   └── General Chat Flow
   ↓
Response Output
```

---

## ⚙️ Technical Decisions

### Workflow-Based Design
The system uses n8n to simplify orchestration and rapid iteration of AI workflows.

### Prompt-Constrained Output
Classification and responses are controlled through structured prompting to improve consistency.

### Conditional Routing
Requests are separated into specialized processing flows to reduce unnecessary AI calls.

---

## 🔄 Current Limitations

- No persistent database
- No authentication system
- No external API wrapper
- No conversation memory
- No automated evaluation/testing pipeline

---

## 📈 Engineering Improvements Planned

### Backend API Layer
Expose workflow functionality through a FastAPI backend.

### Logging & Monitoring
Track request history, errors, and workflow performance.

### Database Integration
Store prompts, request history, and classification results.

### Dockerization
Containerize workflow environment for easier deployment.

### Async Processing
Move longer-running AI tasks into background workers.

---

## 🎯 Project Purpose

This repository is intended to demonstrate:

- AI workflow orchestration
- LLM integration patterns
- Prompt engineering
- Conditional automation logic
- AI-assisted information simplification

---

## ⚠️ Disclaimer

This system does not provide medical advice and is intended for educational and demonstration purposes only.

---

## 📌 Status

Functional prototype / workflow implementation
