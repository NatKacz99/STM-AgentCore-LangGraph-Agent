# STM-AgentCore-LangGraph-Agent

A sample AI agent built using **STM AgentCore Memory** (short-term memory) and **LangGraph**, demonstrated here as a **Personal Fitness Coach**.  
The agent retains information within a single conversation session, enabling more natural interactions without requiring users to repeat information.

---

## Features

- Create and manage short-term memory with AgentCore Memory.
- Integrate with LangGraph for structured agent workflows.
- Tools for retrieving conversation history (`list_events`).
- Personalized responses based on previous messages.
- Test memory persistence across agent sessions.

---

## Technologies

- Python 3.10+
- [STM AgentCore](https://github.com/stm-agentcore)
- [LangGraph](https://github.com/langgraph)
- [LangChain Core](https://github.com/hwchase17/langchain)
- Amazon Bedrock (LLM models, e.g., Claude Haiku 4.5)

---

## Installation

```bash
git clone https://github.com/YourUsername/STM-AgentCore-LangGraph-Agent.git
cd STM-AgentCore-LangGraph-Agent
pip install -r requirements.txt
export AWS_REGION="us-west-2"
export API_KEY="YOUR_KEY"
