# 🤖 Multi-Agent AI Researcher

A **Multi-Agent AI Researcher** designed to automate web-based research, analyze information from multiple sources, generate structured research reports, and critically evaluate the generated report before presenting the final result.

The system uses specialized AI agents and external tools such as **Tavily** for web search and **BeautifulSoup** for extracting content from web pages.

## 🚀 Overview

Traditional research requires manually searching multiple websites, reading large amounts of information, comparing sources, and preparing a final report.

This project automates that workflow using a **multi-agent architecture**, where each agent has a specific responsibility.

The system can:

- Search the web for relevant information
- Collect information from multiple sources
- Scrape useful content from web pages
- Analyze and synthesize the collected information
- Generate a structured research report
- Critique the generated report
- Identify weaknesses, missing information, and potential issues
- Produce a more reliable final research output

## ✨ Key Features

### 🔎 Web Research

Uses **Tavily** to search the web and find relevant sources related to the user's research query.

### 🌐 Web Scraping

Uses **BeautifulSoup** to extract useful information from selected web pages.

### 🤖 Multi-Agent Architecture

Different agents are responsible for different stages of the research process, making the workflow modular and easier to extend.

### 🧠 AI-Powered Analysis

The collected information is analyzed and synthesized by an LLM to identify important findings and relationships between different sources.

### 📝 Report Generation

The system generates a structured research report based on the information gathered during the research process.

### 🔍 Report Critique

A dedicated critique stage evaluates the generated report for:

- Accuracy
- Relevance
- Completeness
- Clarity
- Missing information
- Potential weaknesses
- Unsupported or questionable claims

The critique helps identify problems in the generated research before the final response is produced.

## 🔄 How It Works

The research workflow follows these major stages:

**1. User Query**

The user provides a topic or question that needs to be researched.

**2. Research Agent**

The research agent determines what information is required and performs web searches using Tavily.

**3. Web Content Extraction**

Relevant web pages are processed using BeautifulSoup to extract useful textual information.

**4. Analysis Agent**

The collected information is analyzed and synthesized to identify the most relevant findings.

**5. Report Generation**

A structured research report is generated using the analyzed information.

**6. Critique Agent**

The generated report is reviewed by a separate critique agent that checks its quality, relevance, completeness, and potential weaknesses.

**7. Final Output**

The research findings and critique are used to produce the final research response.

## 🛠️ Technologies Used

- **Python** — Core programming language
- **LLMs** — Reasoning, analysis, report generation, and critique
- **Tavily** — Web search
- **BeautifulSoup** — Web scraping and content extraction
- **LangChain** — LLM and tool integration
- **Multi-Agent Architecture** — Task specialization and orchestration
- **Git & GitHub** — Version control

## 🎯 Use Cases

This system can be useful for:

- Academic research
- Technology research
- AI/ML research
- Market research
- Industry research
- Competitive analysis
- News and trend analysis
- General information gathering

## 🔐 Environment Variables

Create a `.env` file and add your API credentials:

```env
GOOGLE_API_KEY=your_google_api_key
TAVILY_API_KEY=your_tavily_api_key
```

**Never commit your `.env` file or API keys to GitHub.**

For sharing the project, use a `.env.example` file instead:

```env
GOOGLE_API_KEY=
TAVILY_API_KEY=
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Sarfaraj111/Multi-Agent-AI-Researcher-Agent.git
```

Move into the project directory:

```bash
cd Multi-Agent-AI-Researcher-Agent
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Project

After configuring the required environment variables, run the main application:

```bash
python main.py
```

Enter your research topic and the agents will perform the research, analyze the collected information, generate a report, and critique the result.

## 🧪 Example Workflow

```text
User:
"What are the latest developments in Generative AI?"

        ↓

Research Agent
        ↓
Tavily Web Search
        ↓
Relevant Sources
        ↓
BeautifulSoup
        ↓
Extracted Information
        ↓
Analysis Agent
        ↓
Research Report
        ↓
Critique Agent
        ↓
Quality Evaluation
        ↓
Final Research Output
```

## 🔮 Future Improvements

- Add source credibility scoring
- Add citation generation
- Add parallel agent execution
- Add human-in-the-loop review
- Add persistent research memory
- Add RAG-based knowledge retrieval
- Add PDF report generation
- Add Streamlit interface
- Add research history
- Improve factuality and hallucination detection
- Add automated fact-checking

## 📚 What I Learned

This project helped me gain practical experience with:

- Multi-agent AI systems
- Agent orchestration
- LLM-based reasoning
- Tool calling
- Web search integration
- Web scraping
- Prompt engineering
- Automated report generation
- AI-based report evaluation
- API integration
- Building real-world Generative AI applications with Python

## 👨‍💻 Author

**Md Sarfaraj**

B.Tech Student | Generative AI & AI/ML Enthusiast

GitHub:  
https://github.com/Sarfaraj111

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.
