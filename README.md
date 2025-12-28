# 🛳️ CrewAI Agentic Automation

A practical course on building multi-agent systems using the **CrewAI** framework. This repository demonstrates how to orchestrate role-playing autonomous agents that collaborate to solve complex tasks.

## 📚 Course Content

The project covers the following concepts in order:

| Module | Description | Key Concepts |
|:-------|:------------|:-------------|
| **1. Single Agent** | `1_email_agent.ipynb` | Role, Goal, Backstory, Task definition |
| **2. Agent with Tools** | `2_email_agent_with_tool.ipynb` | Giving agents capabilities (e.g., File read, Search) |
| **3. Multi-Agent Crew** | `3_crew.ipynb` | Sequential processing, agent collaboration |
| **4. Crew with Tools** | `4_crew_with_tools.ipynb` | Complex workflows with tool-enabled agents |
| **5. YAML Configuration** | `5_yaml.py` & `config/` | separating config (agents.yaml, tasks.yaml) from logic |
| **6. Memory** | `6_memory.py` | Long-term, short-term, and entity memory |

## 🛠️ Setup Instructions

1. **Environment Setup**:
   - Rename `.sample_env` to `.env`.
   - Add your API keys (OPENAI_API_KEY, SERPER_API_KEY, etc.).

2. **Installation** (using uv):
   ```bash
   uv sync
   ```

3. **Running the Code**:
   - For notebooks: Open in VS Code or PyCharm.
   - For scripts: `uv run python 5_yaml.py`

## 🧠 Core Concepts

- **Agents**: Autonomous units with specific roles (e.g., "Researcher", "Writer").
- **Tasks**: Specific assignments given to agents.
- **Tools**: Skills that agents can use (Web Search, File I/O).
- **Process**: How tasks are executed (Sequential, Hierarchical).
- **Memory**: Ability for agents to recall past interactions and data.