# 🤖 AI Agent with Real-Time Web Search

This project demonstrates how to build a basic AI Agent using LangChain that can:

- Understand user queries  
- Decide whether to use a tool  
- Fetch real-time data from the internet  
- Generate a final summarized response  

---

# 🚀 Features

- 🧠 LLM-based reasoning (OpenAI)
- 🌐 Real-time web search (Tavily)
- 🔁 ReAct-style agent (Reason → Act → Observe)
- ⚡ Tool invocation based on query need

---

# 🧩 Tech Stack

- Python  
- LangChain  
- OpenAI API  
- Tavily API  
- Google Colab  

---

# 🏗️ Project Flow

User Query  
↓  
LLM (understand + decide)  
↓  
IF needed → Tool (Tavily search)  
↓  
Raw Data  
↓  
LLM (summarize)  
↓  
Final Answer  

---

# 🔥 Corrected Explanation

When the user gives a query:

-LLM (OpenAI) first understands the query  
It analyzes what the user is asking  
Then decides:  
Should I use a tool?  
Or answer directly?  

-Decision Step  
If the query needs real-time or external data → tool is used  
Otherwise → LLM answers directly  

-If tool is used (Tavily)  
Tavily searches the internet  
Returns raw text data (not final answer)  

-Second LLM Call  
The raw data is sent back to LLM  

-LLM:  
understands it  
summarizes it  
generates final answer  

-Final Output  
User gets clean, summarized answer  

---

# 🧠 Roles of Components

- Tavily API → Fetches real-time data  
- OpenAI (LLM) → Understands, decides, summarizes  
- Agent → Controls flow and tool usage  

---

# 📓 Google Colab Notebook

Add your Colab link here:  
https://colab.research.google.com/drive/1KItYSqIEsq5goYmBCqXt1xWrjtpfvlYY#scrollTo=R0x5Yfk0ONE7

---

# ⚙️ Installation

Install required libraries:

pip install langchain==0.1.16 langchain-openai==0.0.8 tavily-python

---

# 🔐 API Key Setup

Set your API keys:

OPENAI_API_KEY = your_openai_key  
TAVILY_API_KEY = your_tavily_key  

---

# ⚠️ Notes

- Tool is not always used  
- LLM decides when to call the tool  
- Tavily provides raw data only  
- LLM generates final answer  

---

# 🚀 Future Improvements

- Add frontend (React / Streamlit)  
- Add memory (chat history)  
- Add multiple tools  
- Deploy as web application  

---
