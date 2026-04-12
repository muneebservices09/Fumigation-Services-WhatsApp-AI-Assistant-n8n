# 🛡️ Fumigation-Services-WhatsApp-AI-Assistant

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI-GPT--4o-412991?style=flat&logo=openai&logoColor=white)
![Twilio](https://img.shields.io/badge/Gateway-Twilio-F22F46?style=flat&logo=twilio&logoColor=white)
![Airtable](https://img.shields.io/badge/CRM-Airtable-18BFFF?style=flat&logo=airtable&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Memory-Google_Sheets-34A853?style=flat&logo=googlesheets&logoColor=white)

---

## 🚀 The Solution: Autonomous Service Concierge
In the specialized field of fumigation and pest control, response speed is the primary driver of customer conversion. This project is a **Fully Autonomous WhatsApp AI Receptionist** designed to manage the entire "Pre-Sales" intake funnel with human-level precision.

The system acts as a **Digital Service Specialist**: it engages customers via WhatsApp, utilizes **OpenAI GPT-4o** to diagnose pest issues, gathers critical property data (size, location, urgency), and automatically qualifies leads by syncing confirmed booking data directly into **Airtable**. 🤖🏢✨

---

## 🖼️ System Visualization

### 1. Workflow Orchestration (n8n Architecture)
The complete logic map showing the event-driven trigger, stateful memory retrieval, and AI reasoning paths.
<div align="center">
  <img src="AI-Powered%20WhatsApp%20Receptionist.png" width="100%" alt="n8n WhatsApp AI Receptionist Workflow" style="border-radius:10px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);"/>
</div>

### 2. Conversational Interface (WhatsApp UI)
A real-time look at the AI Agent qualifying a lead and gathering property specifics through natural dialogue.
<div align="center">
  <img src="WhatsApp%20Image%202026-04-12%20at%203.52.30%20PM.jpeg" width="400px" alt="WhatsApp AI Interaction" style="border-radius:15px; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);"/>
  <p><i>Real-time AI triage: Identifying infestation details and property metrics via WhatsApp.</i></p>
</div>

---

## 📊 Business Impact & Engineering Outcomes
This system transforms field service operations by moving from manual intake to intelligent automation:

*   **⚡ 24/7 Lead Capture:** Instantly responds to urgent inquiries at any time, ensuring customers aren't left waiting for a callback.
*   **📉 100% Automated Triage:** Automatically identifies the "infestation type" and property size to provide instant value and qualify lead priority.
*   **🧠 Stateful Conversational Memory:** Retrieves past chat logs from **Google Sheets**, allowing the AI to maintain a continuous dialogue across different messaging sessions.
*   **🛠️ Structured Data Persistence:** Finalized lead data and booking details are pushed to **Airtable**, providing the dispatch team with a perfectly organized service dashboard.

---

## ✅ Problems Solved
- **🛑 High-Frequency Inquiry Fatigue:** No more manually asking repetitive questions like "How many rooms do you have?" or "Where is the property?" 📧
- **🛑 Missed Emergency Leads:** Captures customers facing urgent service issues late at night or over weekends. 🎯
- **🛑 Manual CRM Entry:** Automatically creates structured records in Airtable from messy, unstructured WhatsApp messages. 📂
- **🛑 Context Loss:** The AI remembers exactly what the user previously reported, ensuring a seamless experience for returning customers. 📈

---

## 🧠 Core Technical Pillars

### 1. 📥 Event-Driven Ingress (Twilio Gateway)
The process is initiated by a **Twilio Trigger Node** that monitors a dedicated WhatsApp Business number. The workflow captures raw text and sender metadata, serving as the entry point for the service request.

### 2. 🧠 Stateful Memory & Context Retrieval (Google Sheets)
To provide a human-like experience, the workflow uses a **Google Sheets API** lookup. Before processing a new message, it retrieves the entire history of the sender's phone number, allowing the AI to maintain context and avoid repetitive questioning.

### 3. 🤖 AI Cognitive Logic (OpenAI GPT-4o)
The "Specialist" is a custom-prompted **GPT-4o** agent. It acts as the brain, performing:
- **Natural Language Understanding:** Deciphering diverse ways customers describe service problems.
- **Entity Extraction:** Isolating Name, Property Size, and Service Type.
- **Decision Logic:** Determining when enough information has been gathered to close the lead. 🧠🔍

### 4. 🗄️ Relational CRM Sync (Airtable)
The final stage closes the loop by interfacing with the **Airtable API**. Once a lead is qualified, a custom **JavaScript Code Node** formats the data into a structured JSON payload, creating a new, actionable record for the service technicians. 📡🚀

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | **n8n** (State Management & Orchestration) |
| **🎙️ Gateway** | **Twilio** (WhatsApp & SMS Ingress) |
| **🧠 AI Brain** | **OpenAI GPT-4o** (Conversational Intelligence) |
| **🗄️ CRM Hub** | **Airtable** (Relational Data Persistence) |
| **💾 Memory** | **Google Sheets** (Long-term Conversation Logging) |
| **📜 Scripting** | **JavaScript / Node.js** (Data Parsing & Sanitization) |

---

## ✍️ Author
**Muneeb Ali Khan**
- **GitHub:** [@Muneeb20019](https://github.com/Muneeb20019)
- **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)

---

## 📜 License
This project is licensed under the MIT License.
