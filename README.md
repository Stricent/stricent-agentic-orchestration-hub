# stricent-agentic-orchestration-hub
collection of advanced n8n multi-agent orchestration templates featuring Model Context Protocol (MCP) integration, stateful memory, and human-in-the-loop (HITL) gates.
# 🤖 Stricent Agentic Orchestration Hub

Welcome to the **Stricent Technologies** advanced template repository. While our previous repo focused on foundational n8n workflows, this "Hub" is dedicated to the next generation of automation: **Agentic Workflows.**

## 🚀 Key Features
- **Multi-Agent Systems:** Specialized nodes for Classification, Retrieval, and Execution.
- **MCP Integration:** Templates using the Model Context Protocol to bridge LLMs with internal enterprise data.
- **Stateful Memory:** Workflows that maintain context across long-running business processes.
- **Governance-as-Code:** Built-in "Approval Gates" for secure, human-verified AI actions.

## 📂 Included Templates

### 1. The Autonomous Support Triage Agent
A workflow that classifies incoming support tickets, queries your database for customer history, and drafts a context-aware response for human review.
- **Nodes used:** AI Agent, Postgres (MCP), Gmail, Slack.

### 2. Intelligent Data Visualizer
Turn natural language queries into beautiful charts automatically.
- **Nodes used:** SQL Agent, QuickChart API, Google Sheets.

### 3. "Human-in-the-Loop" Sales Outreach
An AI agent that researches LinkedIn leads and drafts personalized emails, but pauses for a human "OK" before sending.

## 🛠️ Getting Started
1. **Import:** Download the `.json` files from the `/templates` folder.
2. **Setup:** Import them into your n8n instance.
3. **Configure:** Add your API credentials for OpenAI/Claude/Gemini and your specific tools.

---
### 🏢 About Stricent Technologies
We are an **AI Workflow Automation Company** based in India, specializing in **n8n Automation Services**. We help businesses scale by building the "brains" behind their operations.

🌐 [Visit Stricent.in](https://stricent.in) | ✍️ [Read our Technical Blog](https://stricent.hashnode.dev)
