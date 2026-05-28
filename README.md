# ResearchMind 🔬⚡

### Multi-Agent AI Research System

ResearchMind is a powerful **multi-agent AI research assistant** inspired by the **Deep Research capabilities** of modern LLM platforms like ChatGPT, Claude, Gemini, and Perplexity.

The system autonomously:

* searches the web,
* gathers reliable sources,
* scrapes detailed content,
* generates structured research reports,
* and critically reviews its own output using AI agents.

Built using **LangChain**, **Mistral AI**, **Tavily Search**, and **Streamlit**.

---

# 🚀 Live Demo

🔗 https://multi-agent-system-96hk5izp6m6fxjxqkd34yv.streamlit.app

---

# ✨ Features

* 🔎 Autonomous AI Search Agent
* 🌐 Real-time Web Search using Tavily
* 📄 Web Scraping & Content Extraction
* ✍️ AI Research Report Writer
* 🧠 AI Critic / Reviewer Agent
* 📚 Structured Research Pipeline
* 🎨 Modern Cyberpunk UI
* 🌙 Dark Theme Interface
* 📥 Markdown Report Download
* ☁️ Cloud Deployment with Streamlit

---

# 🧠 How It Works

ResearchMind uses a **multi-agent architecture** similar to advanced AI research systems.

## Pipeline Architecture

```text
User Query
    ↓
Search Agent
    ↓
Reader Agent
    ↓
Writer Chain
    ↓
Critic Chain
    ↓
Final Research Report
```

---

# 🤖 Agents

## 1. Search Agent

Searches the internet for:

* recent information
* trusted sources
* relevant URLs
* research material

Powered by:

* Tavily Search API

---

## 2. Reader Agent

Scrapes and extracts detailed content from selected web pages.

Capabilities:

* content extraction
* summarization
* relevance filtering

---

## 3. Writer Chain

Generates:

* introduction
* key findings
* conclusions
* structured research reports
* citations & sources

---

## 4. Critic Chain

Acts like an AI reviewer.

It:

* scores the report
* identifies weaknesses
* suggests improvements
* evaluates research quality

---

# 🛠️ Tech Stack

## AI / LLM

* LangChain
* Mistral AI
* Tavily Search API

## Frontend

* Streamlit
* Custom CSS

## Backend

* Python
* Multi-Agent Architecture

## Deployment

* Streamlit Community Cloud

---

# 📸 Screenshots

## Home Page

<img width="1600" height="812" alt="WhatsApp Image 2026-05-28 at 15 50 59" src="https://github.com/user-attachments/assets/c4181168-6625-4d30-ba32-b54b34b42c1f" />


* Futuristic cyberpunk interface
* Interactive research pipeline

## Research Generation

* Search agent output
  <img width="1600" height="812" alt="WhatsApp Image 2026-05-28 at 15 50 59" src="https://github.com/user-attachments/assets/0b55ff1c-72e2-479a-be13-cb55e11b041b" />

* Reader agent scraping
* Final report generation
  <img width="1600" height="733" alt="WhatsApp Image 2026-05-28 at 15 52 19" src="https://github.com/user-attachments/assets/fa9a4b5f-f0dc-4603-90a1-864c554cf777" />
  <img width="1600" height="793" alt="WhatsApp Image 2026-05-28 at 15 52 33" src="https://github.com/user-attachments/assets/e8463c5f-ac61-420c-9ce5-0e53b6b07209" />

* Critic feedback analysis
<img width="1600" height="793" alt="WhatsApp Image 2026-05-28 at 15 52 33" src="https://github.com/user-attachments/assets/58b11f52-01a0-45e9-9f79-b08fdae753b9" />

---

# ⚡ Installation

## 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/multi-agent-system.git

cd multi-agent-system
```

---

## 2. Create Virtual Environment

```bash
uv venv
```

Activate environment:

### Windows

```bash
.venv\Scripts\activate
```

---

## 3. Install Dependencies

```bash
uv pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create `.env`

```env
MISTRAL_API_KEY=your_key
TAVILY_API_KEY=your_key
OPENWEATHER_API_KEY=your_key
```

---

# ▶️ Run Locally

```bash
streamlit run app.py
```

---

# ☁️ Deployment

This project is deployed using Streamlit Cloud.

To deploy:

1. Push project to GitHub
2. Connect repository to Streamlit Cloud
3. Add secrets in Streamlit settings
4. Deploy

---

# 📂 Project Structure

```text
multi-agent-system/
│
├── app.py
├── agents.py
├── tools.py
├── requirements.txt
├── styles/
├── assets/
├── README.md
└── .streamlit/
```

---

# 🎯 Future Improvements

* Vector Database Memory
* Recursive Research Loops
* Multi-page Deep Scraping
* PDF Export
* Live Streaming Responses
* Citation Grounding
* LangGraph Integration
* Async Agent Execution
* Voice Research Assistant
* AI Research History

---

# 🌟 Inspiration

Inspired by:

* ChatGPT Deep Research
* Claude AI Research
* Gemini Research Tools
* Perplexity AI
* Autonomous AI Agents

---

# ⭐ If You Like This Project

Star the repository and share it with others 🚀
