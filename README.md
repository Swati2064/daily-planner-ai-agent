# 📅 Daily Planner AI Agent using n8n

An AI-powered Daily Planner built with **n8n**, **OpenAI GPT-5 Mini**, and **Google Sheets**. This workflow allows users to interact with an intelligent chatbot that retrieves planner information directly from a Google Sheet.

---

## 🚀 Features

* 🤖 AI-powered chatbot
* 📅 Daily planner assistance
* 📊 Google Sheets integration
* 💬 Chat Trigger interface
* ⚡ Built using n8n workflow automation
* 🔗 OpenAI GPT-5 Mini integration

---

## 🛠️ Tech Stack

* n8n
* OpenAI GPT-5 Mini
* Google Sheets API
* AI Agent (LangChain Node)
* JSON Workflow

---

## 📂 Workflow Overview

The workflow consists of the following nodes:

1. **Chat Trigger**

   * Starts the conversation when a user sends a message.

2. **AI Agent**

   * Processes user requests using the language model.

3. **OpenAI Chat Model**

   * Generates intelligent responses.

4. **Google Sheets Tool**

   * Retrieves planner data from Google Sheets.

---

## 🔄 Workflow Architecture

```
User
   │
   ▼
Chat Trigger
   │
   ▼
AI Agent
 ├──────────────► OpenAI GPT-5 Mini
 │
 └──────────────► Google Sheets
                     │
                     ▼
             Planner Information
                     │
                     ▼
                Response to User
```

---

## 📁 Project Structure

```
daily-planner-ai-agent/
│
├── daily_planner_using_n8n.json
├── README.md
└── assets/
```

---

## ⚙️ Installation

1. Clone the repository.

```bash
git clone https://github.com/your-username/daily-planner-ai-agent.git
```

2. Open n8n.

3. Import the workflow.

4. Configure:

   * OpenAI credentials
   * Google Sheets OAuth credentials

5. Activate the workflow.

---

## 📌 Requirements

* n8n
* OpenAI API Access
* Google Account
* Google Sheets OAuth Credentials

---

## ▶️ How It Works

1. User sends a chat message.
2. Chat Trigger starts the workflow.
3. AI Agent understands the request.
4. Google Sheets is queried for planner information.
5. GPT-5 Mini generates a natural response.
6. The chatbot replies to the user.

---

## 📷 Demo

Import the workflow into n8n and start chatting with your AI Daily Planner.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Open a Pull Request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Swati Jadhav**

GitHub: https://github.com/swati2064
