# 📈 AI Investment Strategist

A multi-agent AI-powered financial analyst that generates **personalized investment reports** using real-time stock data, company insights, and market performance analysis. Built with Streamlit, Yahoo Finance API, Plotly, and Google Gemini via Agno AI.

![Image](https://github.com/user-attachments/assets/fd3a2488-651c-447b-a720-b4878b7901a6)

---
## 🎥 Demo

Watch the full walkthrough of the **AI Investment Strategist** in action:

[![Watch the Demo](https://www.dropbox.com/scl/fi/vvx8r8lr60drtltk1f7nm/Ai-Investment-Strategist.mp4?rlkey=5ychfsbw5nhq747mq1b3bpu1g&st=yqz9izvs&dl=0)

> 📊 Real-time stock analysis • 🧠 Multi-agent decision making • 📈 Final investment report generation
> 
## 🚀 Features

- 🔍 Real-time stock performance analysis (6-month trend)
- 🧠 Multi-agent reasoning powered by Google Gemini
- 🏢 Company profile, sector, market cap, and latest news summary
- 📊 Interactive line charts with Plotly
- 🗞️ Final investment report with ranked stock recommendations
- 💽 Streamlit-based UI for easy interaction

---

## 🧠 Agentic AI Architecture

This app follows a **Chain-of-Experts multi-agent architecture**:

| Agent Name         | Role        | Function                                                               |
|--------------------|-------------|------------------------------------------------------------------------|
| `market_analyst`   | Analyst     | Analyzes 6-month stock performance using Yahoo Finance data            |
| `company_researcher` | Researcher | Summarizes company fundamentals and news                               |
| `stock_strategist` | Strategist  | Recommends stocks based on risk-reward and market trends               |
| `team_lead`        | Coordinator | Compiles and ranks all insights into a final report                    |

Agents communicate through task delegation and sequential reasoning. The app grounds data in real-time stock performance and uses LLMs to synthesize insights.

---

## 🛠️ Tech Stack

- **Frontend:** [Streamlit](https://streamlit.io/)
- **Stock Data:** [Yahoo Finance via yfinance](https://pypi.org/project/yfinance/)
- **Charts:** [Plotly](https://plotly.com/)
- **LLM Agent Framework:** [Agno AI](https://pypi.org/project/agno/)
- **LLM Backend:** [Google Gemini (via API)](https://deepmind.google/technologies/gemini/)
- **Language:** Python 3.10+

---

## 🧹 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/ai-investment-strategist.git
cd ai-investment-strategist
