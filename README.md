# 🤖 AI Agent Automation using n8n

This project showcases an **AI-powered conversational agent** built using **n8n**, designed to automate intelligent responses to user queries by combining a large language model, memory, and utility tools within a visual workflow.

The AI Agent listens for incoming chat messages, processes them using an integrated AI model, retains conversational context through memory, and dynamically uses tools such as date/time and calculations to generate accurate and context-aware responses.

---

## 📌 Project Overview

The AI Agent workflow is triggered whenever a chat message is received. It routes the message to an AI Agent node that orchestrates:

- Natural language understanding  
- Context retention using memory  
- Tool usage for real-time data and calculations  
- Intelligent response generation  

This project demonstrates how **low-code automation** can be combined with **AI capabilities** to build scalable, production-ready conversational systems.

---

## 🛠️ Tools & Technologies Used

- **🔁 n8n** – Workflow automation and orchestration platform  
- **🤖 AI Agent Node** – Central intelligence layer for reasoning and responses  
- **🧠 Groq Chat Model** – Large Language Model for fast and accurate responses  
- **💾 Simple Memory** – Maintains conversation context across messages  
- **🧮 Calculator Tool** – Handles numeric computations on demand  
- **⏰ Date & Time Tool** – Provides real-time date and time information  
- **💬 Chat Trigger** – Activates the workflow upon receiving user messages  

---

## 🔄 Workflow Architecture

1. **Chat Message Trigger**  
   - Listens for incoming user messages  

2. **AI Agent Processing**  
   - Interprets user intent  
   - Uses the LLM for reasoning and response generation  
   - Retrieves relevant conversation history from memory  

3. **Tool Integration**  
   - Invokes calculator or date/time tools when required  
   - Enhances responses with real-time and computed data  

4. **Response Delivery**  
   - Sends intelligent, contextual replies back to the user  

---

## 📸 Screenshots

### 🧩 AI Agent Workflow (n8n Editor)
![AI Agent Workflow](./screenshots/Screenshot%202025-12-02%20at%2010.22.27%20AM.png)

### 💬 Chat Interaction with AI Agent
![Chat Interaction](./screenshots/Screenshot%202025-12-02%20at%2010.22.45%20AM.png)

### ⚙️ AI Agent Execution & Logs
![Execution Logs](./screenshots/Screenshot%202025-12-02%20at%2010.23.39%20AM.png)

---

## 💼 Business Problem

Building AI-powered assistants often requires complex backend logic and infrastructure. This project addresses the need for a **simpler, low-code approach** to creating intelligent chat agents that can reason, remember, and act using external tools.

---

## 🎯 Project Goal

The goal of this project is to demonstrate how **AI agents can be built visually using n8n**, enabling developers and analysts to:

- Rapidly prototype AI assistants  
- Integrate LLMs with business workflows  
- Build scalable, maintainable conversational automation  

---

## 🚀 Key Features

- Context-aware conversations using memory  
- Tool-augmented AI responses  
- Modular and extensible workflow design  
- Real-time chat-based interaction  
- Low-code implementation suitable for rapid deployment  

---

## 🔮 Future Enhancements

- Integration with external APIs (CRM, ticketing systems, databases)  
- Multi-user session handling  
- Role-based AI behavior  
- Deployment as a customer support or HR assistant  

---

## 👤 Author

**Prasad Darandale**  
AI Automation | Data Analytics | Workflow Engineering  

---

⭐ If you found this project useful, consider starring the repository!
