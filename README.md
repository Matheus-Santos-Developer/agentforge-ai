# AgentForge AI

AgentForge AI is a lightweight Python AI agent project designed to demonstrate how modern **AI agents can reason, use tools, and execute tasks autonomously** using large language models.

This project showcases the fundamental architecture behind agent-based systems, including tool usage, decision-making, and automated task execution.

It was built as part of a hands-on exploration of **AI agent development, orchestration, and intelligent automation using Python**.

---

## 🚀 Features

* 🤖 **Autonomous AI Agent**
  Uses a large language model to analyze tasks and determine which tools to use.

* 🧰 **Tool Integration**
  The agent can interact with external tools to gather information or perform actions.

* 🧠 **Reasoning Loop**
  The system processes a task, decides on actions, executes tools, and refines the response.

* ⚡ **Fast Dependency Management**
  Uses **uv** for extremely fast Python package installation and environment management.

* 🧩 **Modular Architecture**
  Easy to extend with additional tools and agent capabilities.

---

## 🛠 Tech Stack

* Python
* LLM-based agent architecture
* Tool-calling system
* uv (Python package manager)
* API integrations

---

## 📂 Project Structure

```
agentforge-ai/
│
├── main.py            # Main AI agent execution
├── tools.py           # Tool definitions used by the agent
├── pyproject.toml     # Project dependencies
└── README.md          # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/Matheus-Santos-Developer/agentforge-ai.git
```

### 2. Navigate into the project

```
cd agentforge-ai
```

### 3. Install dependencies using uv

```
uv sync
```

This will automatically:

* create the virtual environment
* install all project dependencies

---

## ▶️ Running the AI Agent

Run the project with:

```
uv run main.py
```

The AI agent will process the task, decide which tools to use, and execute the workflow automatically.

---

## 📚 Learning Goals

This project explores key concepts behind modern AI systems:

* AI agent architecture
* tool-based reasoning
* prompt orchestration
* automated task execution
* practical AI engineering workflows

---
