# CrewAI Email Agent

CrewAI is a framework designed for **role-based orchestration of AI agents** with minimal customization.  
Instead of building complex pipelines, you simply define **roles, goals, and tasks** — and let the agents handle the rest.  

This project sets up an **Email Assistant Agent** powered by **Gemini API** for LLM intelligence.  

---

## 🛠️ Environment Setup

- **IDE:** PyCharm  
- **Package Manager:** [uv](https://docs.astral.sh/uv/getting-started/installation/)  
- **LLM:** Gemini API  

---

## 📌 Steps to Setup

### 1️⃣ Initialize Project
```
uv init crewai-email-agent
```

### 2️⃣ Add dependencies
```
uv add crewai[tools]
```
### 3️⃣ Configure .env with your Gemini API key
```
GEMINI_API_KEY=your_api_key
```
### 🚀 Next Steps

Define your Agents, Tasks, and Crew in email_agent.ipynb or a Python script. Run the agent to enhance and manage your emails.