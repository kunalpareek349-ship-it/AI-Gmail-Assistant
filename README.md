# 📧 AI Gmail Assistant
![n8n](https://img.shields.io/badge/Built%20with-n8n-orange)
![Google Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blue)
![Gmail API](https://img.shields.io/badge/API-Gmail-red)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Working-success)

An AI-powered Gmail Assistant built with **n8n**, **Google Gemini**, and the **Gmail API**. The assistant understands natural language and performs Gmail operations such as reading, sending, replying, archiving, deleting, starring, and marking emails as read or unread.

---

## ✨ Features

- 📩 Read the latest email
- 📬 Read unread emails
- 📤 Send emails
- 💬 Reply to emails
- 🗂 Archive emails
- 🗑 Delete emails
- ✅ Mark emails as read
- 📭 Mark emails as unread
- ⭐ Star emails
- ✩ Unstar emails
- 🤖 Natural language interaction
- 🧠 AI-powered tool selection

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow automation |
| Google Gemini | Natural language understanding |
| Gmail API | Email operations |
| AI Agent | Tool selection and orchestration |
| Simple Memory | Conversation context |

---

## 🏗 Architecture

```text
User
   │
   ▼
Chat Trigger
   │
   ▼
AI Agent (Google Gemini)
   │
   ▼
Chooses Gmail Tool
   │
   ├── Read Email
   ├── Send Email
   ├── Reply Email
   ├── Archive Email
   ├── Delete Email
   ├── Mark Read
   ├── Mark Unread
   ├── Star Email
   └── Unstar Email
   │
   ▼
Gmail API
   │
   ▼
Response to User
```

---

## 🚀 Example Commands

```text
Read my latest email.

Read my latest unread email.

Reply to my latest email saying:
Thanks! I'll get back to you soon.

Archive my latest email.

Delete my latest email.

Mark my latest email as unread.

Star my latest email.

Send an email to john@example.com with subject Meeting and message See you tomorrow.
```

---

## 📂 Repository Structure

```text
gmail-ai-assistant/
│
├── README.md
├── LICENSE
├── .gitignore
├── gmail-ai-assistant.json
│
├── screenshots/
│
└── docs/
```

---

## ⚙️ Setup

1. Clone the repository.
2. Import the workflow into n8n.
3. Configure Gmail credentials.
4. Configure a Google Gemini API key.
5. Open the Hosted Chat.
6. Start interacting using natural language.

---

## 📌 Current Capabilities

- Read emails
- Send emails
- Reply to emails
- Archive emails
- Delete emails
- Mark emails as read or unread
- Star and unstar emails

---

## 🔮 Future Improvements

- Gmail search with advanced filters
- Calendar integration
- Attachment management
- Voice interface

---

## 👨‍💻 Author

**Kunal Pareek**

Built as a portfolio project demonstrating AI-powered workflow automation using n8n.
