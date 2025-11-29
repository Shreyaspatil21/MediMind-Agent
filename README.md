# 🩺 HIA (Health Insights Agent)
An AI-powered intelligent agent that analyzes blood reports and provides detailed, personalized health insights using a multi-model LLM architecture.

<div align="center">
  <img src="public/Demo.gif" alt="Demo GIF" width="800" />
  <br/><br/>
  <img src="public/HIA_demo.gif" alt="HIA Demo GIF" width="800" />
</div>

---

<div align="center">

### 📊 GitHub Stats & Badges

![Stars](https://img.shields.io/github/stars/Shreyaspatil21/MediMind-Agent?style=flat-square)
![Forks](https://img.shields.io/github/forks/Shreyaspatil21/MediMind-Agent?style=flat-square)
![Issues](https://img.shields.io/github/issues/Shreyaspatil21/MediMind-Agent?style=flat-square)
![Pull Requests](https://img.shields.io/github/issues-pr/Shreyaspatil21/MediMind-Agent?style=flat-square)
![License](https://img.shields.io/github/license/Shreyaspatil21/MediMind-Agent?style=flat-square)

</div>

<p align="center">
  <a href="#-features">Features</a> |
  <a href="#-tech-stack">Tech Stack</a> |
  <a href="#-installation">Installation</a> |
  <a href="#-screenshots">Screenshots</a> |
  <a href="#-contributing">Contributing</a> |
  <a href="#-author">Author</a>
</p>

---

## 🌟 Features

- 🤖 **Multi-Agent AI Architecture** with cascading Groq models  
- 🧠 **In-context learning** from previous analyses  
- 🔬 **Blood report analysis** with personalized insights  
- 📄 **PDF upload**, validation & text extraction (20MB max)  
- 🔐 **Supabase Authentication**  
- 💾 **Session history** saved  
- ⚡ **Fast, responsive Streamlit UI**  

---

## 🛠️ Tech Stack

### **Frontend**
- Streamlit  

### **AI Models (Groq API)**
- meta-llama/llama-4-maverick-17b-128e-instruct  
- llama-3.3-70b-versatile  
- llama-3.1-8b-instant  
- llama3-70b-8192 (fallback)

### **Backend**
- Python  
- Supabase  
- PDFPlumber  
- python-magic  

---

## 🚀 Installation

### **Requirements**
- Python 3.8+  
- Streamlit 1.30+  
- Groq API key  
- Supabase account  

---

## 🔧 Getting Started

```bash
git clone https://github.com/Shreyaspatil21/MediMind-Agent.git
cd MediMind-Agent

pip install -r requirements.txt

streamlit run app.py

