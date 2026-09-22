# Hi there, I'm Waqas Sharif 👋

### AI Engineer · LLM Evaluation and Reliability · Agentic Systems
**I build production agentic AI systems, then measure how they fail.**

I treat LLMs as stochastic components that need deterministic guardrails,
typed state management and a real evaluation harness, not as magic boxes.
Most of my work is the second half of that sentence: building the system is
the easy part, proving it behaves is not.

🟢 **Status:** BE Software Engineering, KIET, completed August 2026.
Open to remote AI engineering roles. **No visa sponsorship required.**
Also preparing Masters applications for Winter 2027/28.

---

### What the work looks like

| 🔬 **Evaluation and reliability** | 🏗️ **Production systems** |
| :--- | :--- |
| A 46-file behavioural test suite of 592 automated tests, 19 behavioural probes using paired before-and-after measurement, 60 per-turn traces across five personas, and three named reproducible LLM failure modes | Agentic systems with typed state, concurrent-write reducers, deterministic quality gates and streaming, recorded across 334 documented build and audit sessions |
| *Evaluation Design · Behavioural Testing · Red Teaming · Token Sampling · LangSmith* | *LangGraph · Google ADK · FastAPI · Flutter · SSE Streaming* |

---

### 🚀 Projects

| Project | Description | Stack |
| :--- | :--- | :--- |
| **Rahzaan · AI Career Guidance** *(Source private · [Case Study](https://waqas01cp.github.io/Rahzaan/) · [Live Demo](https://fyp-career-guidance.vercel.app/#/onboarding))* | Deployed career counselling platform for Pakistani secondary school students. Maintained through an evaluation harness of 19 behavioural probes and 592 automated tests over a 24-node LangGraph pipeline, first response cut from 20–25s to 3.7s. 265-item psychometric assessment stack, 9-criterion reflection gate, live SSE streaming, 29-route Flutter frontend. The case study documents the failures as well as the build. | `LangGraph` `FastAPI` `Flutter` `PostgreSQL` |
| **[Autonomous Research Concierge](https://github.com/Waqas01CP/Autonomous-Research-Concierge)** | Multi-agent research pipeline. An intent synthesiser compacts chat history into a research directive before three search agents fan out concurrently. Per-call session isolation, and a deterministic code-based filter ahead of all tool access so the guardrail is structurally bypass-resistant rather than prompt-enforced. Deployed on Railway. | `Google ADK` `Docker` `Python` |
| **[Applied LLM Workflow Research](https://github.com/Waqas01CP/Applied-LLM-Workflow-Research)** | Behavioural study of Gemini 2.5 Pro. Names three reproducible failure modes (Optimal Answer Trap, Final Synthesis Bias, Conversational Gravity), each with documented prompt sequences. Includes controlled sampling experiments, 1M-token context stress tests, and context-ordering trials showing a ~30% retrieval error rate when context follows rather than precedes the instruction. | `Python` `Streamlit` |
| **[Crypto Accumulation Scanner](https://github.com/Waqas01CP/Crypto-Accumulation-Scanner)** | Scans 1,200+ cryptocurrencies daily across CoinMarketCap and MEXC Futures. Classifies price action into 7 accumulation signatures and applies a log-log regression volatility baseline derived from 2020–2024 market data, normalised by market-cap tier so outliers surface instead of size artefacts. | `Google Apps Script` `JavaScript` `CoinMarketCap API` |
| **[WordPy Solver](https://github.com/Waqas01CP/WordPy-Solver)** | Autonomous Wordle solver reading game state by sampling tile pixel colour instead of OCR, since the corner region is pure background regardless of font or antialiasing. Constraint-based filtering with a greedy information-gain heuristic. 85%+ solve rate within six guesses across a 5,922-word list, covered by a 36-test suite. | `Python` `Pillow` |

---

### 🛠️ Stack

**Agentic AI & LLM**
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Google ADK](https://img.shields.io/badge/Google%20ADK-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=for-the-badge)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=for-the-badge)

**Languages**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

**Backend & Infrastructure**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

**Frontend**
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)

**Practices:** Context Engineering · Prompt Engineering · Evaluation Design · Behavioural Testing · Red Teaming · Chain of Density · Tree of Thoughts · Token Sampling

**Also:** C and C#, used throughout my degree; C++ and Java from coursework. .NET and ASP.NET from coursework.

---

### 📊 Stats

![GitHub overview](https://github.com/Waqas01CP/github-stats/blob/generated/overview.svg#gh-dark-mode-only)
![GitHub overview](https://github.com/Waqas01CP/github-stats/blob/generated/overview.svg#gh-light-mode-only)
![Language breakdown](https://github.com/Waqas01CP/github-stats/blob/generated/languages.svg#gh-dark-mode-only)
![Language breakdown](https://github.com/Waqas01CP/github-stats/blob/generated/languages.svg#gh-light-mode-only)

<sub>Stats images generated by <a href="https://github.com/jstrieb/github-stats">jstrieb/github-stats</a>.</sub>

---

### 💼 Experience

**AI Automation Engineer (Intern), HubIT**, June 2026 to July 2026, Karachi.

- Built a **Python** pipeline extracting recurring utility documents into **schema-validated billing records** for a residential property management client, replacing a manual data entry step; enforced strict validation with repair and retry on malformed model output, blocking bad records before they reached billing.
- Designed the **reconciliation stage** matching extracted records to individual units, hardening it against silent mis-mapping and dropped records with validation and structured failure logging, and building up a test suite from each failure found.

**Engineering Intern, Pakistan Aeronautical Complex (PAC) Kamra**, Jan to Feb 2024.
Analysed systems integration workflows, avionics production pipelines and precision manufacturing across the JF-17 Thunder programme.

---

### 🔭 Currently

- Extending **Rahzaan** so any student in Karachi can use it
- Independent research on LLM behavioural failure modes: context anchoring and long-horizon drift
- Preparing Masters applications for AI and intelligent systems programmes, Winter 2027/28

---

<div align="center">
  <a href="https://www.linkedin.com/in/ma-waqas-sharif/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:ma.sharif.waqas@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>
