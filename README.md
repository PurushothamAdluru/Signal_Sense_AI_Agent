#  SignalSense: AI Intent & Sentiment Agent + Live Analytics Dashboard

SignalSense is a lightweight AI system that reads messages the way a human would. It interprets intent, sentiment, urgency, and lead readiness, then visualizes everything through a clean, real-time Streamlit dashboard.

No APIs.  
No paid tools.  
Fully local.  
Runs on Python, Ollama, and Streamlit.

---

##  What This Project Does

SignalSense has two core components:

### **1. AI Agent (Message Interpreter)**
The agent reads any incoming text and instantly understands:
- **Intent** (pricing, demo request, support, etc.)
- **Sentiment** (positive, neutral, negative)
- **Lead Score** (how serious or ready the user is)
- **Recommended Action** (sales follow-up, support escalation, nurture, etc.)

Each processed message is saved as clean structured data.

### **2. Real-Time Analytics Dashboard**
Built using Streamlit, the dashboard shows:
- Total conversations  
- Intent distribution  
- Sentiment breakdown  
- Lead score histogram  
- Filters by intent and sentiment  
- Full conversation log  

This turns scattered conversations into clear, actionable patterns.

---

##  Why This Matters

Modern teams are overloaded with messages from support tickets, DMs, demo forms, and customer chats.  
Humans can instantly sense tone and intention. Systems usually can’t.

SignalSense bridges that gap by:
- Understanding conversations automatically  
- Scoring readiness  
- Surfacing meaningful patterns  
- Giving teams clarity without complex ML or expensive tools  

Even as a small prototype, it shows how much intelligence can be unlocked with a simple, local setup.

---

##  Tech Stack

### **Backend & Logic**
- Python 3  
- Ollama (local LLM inference)  
- Lightweight rule-based reasoning  
- JSON for storage  

### **Frontend & Visualization**
- Streamlit  
- Plotly  

### **Data Flow**
Message → AI agent → structured data → dashboard visualization

---

## 📁 Project Structure

