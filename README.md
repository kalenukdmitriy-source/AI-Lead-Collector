<div align="center">

# 🚀 AI Lead Collector

### AI-Powered Lead Qualification & Automation with n8n

<img src="Banner.png" width="100%" alt="AI Lead Collector">

<br>

![n8n](https://img.shields.io/badge/n8n-Automation-FF6D5A?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)

</div>

---

# 📌 About

**AI Lead Collector** is a fully automated lead qualification system built with **n8n**.

The workflow collects customer requests from **Google Forms**, sends them to **OpenAI** for AI-powered qualification, stores all information in **Google Sheets**, and instantly delivers notifications to **Telegram**.

This project demonstrates how AI can automate repetitive business processes while improving response speed and lead quality.

---

# ✨ Features

✅ Google Forms integration

✅ AI Lead Qualification

✅ Google Sheets CRM

✅ Telegram Notifications

✅ Automatic Workflow

✅ Easy Deployment

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| n8n | Workflow Automation |
| OpenAI API | AI Lead Qualification |
| Google Forms | Lead Collection |
| Google Sheets | CRM Database |
| Telegram Bot API | Notifications |

---

# 📊 Workflow

```text
                Google Forms
                      │
                      ▼
             Receive New Lead
                      │
                      ▼
             OpenAI Qualification
                      │
        ┌─────────────┴─────────────┐
        ▼                           ▼
 High Quality Lead          Low Quality Lead
        │                           │
        └─────────────┬─────────────┘
                      ▼
              Google Sheets CRM
                      │
                      ▼
            Telegram Notification
```

---

# 📸 Screenshots

## Workflow

![](screenshots/общий%20workflow%20в%20n8n.png)

---

## Google Sheets CRM

![](screenshots/заполненную%20Google%20Таблицу....png)

---

## Telegram Notification

![](screenshots/сообщение%20в%20Telegram.png)

---

## Updated Lead Status

![](screenshots/сообщение%20в%20Telegram%20(2).png)
---

## 📁 Project Structure

```text
AI-Lead-Collector/
│
├── Banner.png
├── README.md
│
├── workflows/
│   └── AI Lead Collector _ Google Forms → AI → CRM → Telegram.json
│
└── screenshots/
    ├── общий workflow в n8n.png
    ├── заполненную Google Таблицу.png
    ├── сообщение в Telegram.png
    └── сообщение в Telegram (2).png
```

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/kalenukdmitriy-source/ai-lead-collector.git
```

Import the workflow into **n8n**

Configure:

- OpenAI API
- Google Credentials
- Telegram Bot
- Google Forms

Activate the workflow.

---

# 💼 Business Value

- Reduce manual lead processing
- Instant customer notifications
- AI-powered lead qualification
- Faster response time
- Better sales efficiency
- Easy integration with existing CRM

---

# 🎯 Perfect For

- Sales Teams
- Agencies
- Freelancers
- CRM Automation
- AI Workflow Portfolio
- Business Process Automation

---

# ⭐ Repository

If you found this project useful, consider giving it a ⭐.

It helps support the project and motivates future improvements.
