# 🤖 WhatsApp AI Agent (n8n Workflow)

## 🇬🇧 English Version

### 📘 Overview
The **WhatsApp AI Agent** is an intelligent automation workflow built with **n8n**, integrating **OpenAI** to handle WhatsApp messages automatically.  
It can receive messages via the **WhatsApp Cloud API**, process them with AI using LangChain tools (like Wikipedia, Calculator, Gmail), and reply smartly through WhatsApp.

---

### ⚙️ Features
- 🤖 Smart AI responses powered by OpenAI (GPT models)  
- 🧠 Memory system to maintain chat context  
- 🌐 Integration with WhatsApp Cloud API  
- 📧 Email sending via Gmail node  
- 🔢 Calculator and Wikipedia tools for useful answers  
- 💾 Easy import/export through JSON file  
- 🧩 Fully customizable inside n8n

---

### 🧰 Requirements
- [n8n](https://n8n.io/) installed (self-hosted or on n8n.cloud)  
- **WhatsApp Cloud API** account (via Facebook Developer)  
- **OpenAI API Key**  
- (Optional) **Gmail account** for email node  

---

### 🚀 How to Run
1. Open your **n8n** workspace.  
2. Click the three dots (⋮) → **Import from File** → upload `14-Whatsapp-Test-Agent.json`.  
3. Open each credential node and connect your accounts:  
   - WhatsApp Cloud (Access Token + Phone ID)  
   - OpenAI API key  
   - Gmail OAuth (if needed)  
4. Activate the workflow.  
5. Send a WhatsApp message to your registered number and watch the AI reply automatically 🎉  

---

### 📂 Files
- `14-Whatsapp-Test-Agent.json` → main workflow file for n8n  
- `README.md` → project documentation

---

### 👨‍💻 Developer
Developed by **Felobateer**  
Built with ❤️ using **Python, n8n, and OpenAI**

---

### 🏷️ License
This project is open-source and available for learning and personal use.

