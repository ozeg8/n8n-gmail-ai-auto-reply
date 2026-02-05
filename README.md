# 🤖 AI-Powered Gmail Auto Label & Smart Reply (n8n)
> AI-powered Gmail automation workflow built with n8n for smart labeling and automated replies.



This workflow automatically classifies incoming Gmail messages, applies the correct labels, and sends a context-aware auto-reply using AI.

It is designed to reduce response time, keep inboxes organized, and provide a professional first response to incoming emails.

[![Workflow Overview](https://raw.githubusercontent.com/ozeg8/n8n-gmail-ai-auto-reply/main/Screenshot%202026-02-06%20at%2000-01-06%20▶️%20My%20workflow%20-%20n8n%20DEV.png)](https://github.com/ozeg8/n8n-gmail-ai-auto-reply/blob/main/Screenshot%202026-02-06%20at%2000-01-06%20▶️%20My%20workflow%20-%20n8n%20DEV.png)


---

## 🚀 Features

- 📩 Triggers on new incoming Gmail messages  
- 🧠 Uses AI to understand email intent  
- 🏷 Automatically applies Gmail labels based on topic  
- 💬 Sends a smart reply in the same email thread  
- 🔁 Prevents creating new email threads  
- 🧩 Fully customizable and template-ready  

---

## 🧠 Email Categories

The workflow classifies emails into the following categories:

- Course Request  
- Consultation Request  
- Payments  
- Miscellaneous  

Each category:
- Receives a dedicated Gmail label  
- Triggers a category-specific auto-reply message  

---

## 🛠 How It Works (High Level)

1. A new email arrives in Gmail  
2. The email content is extracted and summarized  
3. AI analyzes the message intent  
4. A Switch node routes the flow to the correct category  
5. The email is labeled accordingly  
6. A professional reply is sent within the same thread  

---

## 🔐 Credentials & Security

⚠️ This workflow does **NOT** include any credentials.

Before running the workflow, you must connect your own:

- Gmail account  
- OpenAI (or compatible) API credentials  

No API keys, tokens, or sensitive information are included in the exported workflow.

---

## ⚙️ Requirements

- n8n (self-hosted or cloud)  
- Gmail account with API access  
- OpenAI-compatible chat model credentials  

---

## 🧩 Setup Instructions

1. Import the workflow JSON into n8n  
2. Connect your Gmail credentials in all Gmail nodes  
3. Connect your AI / OpenAI credentials in the AI nodes  
4. Review and customize reply messages if needed  
5. Activate the workflow  

That’s it 🎉

---

## ✨ Customization Ideas

- Add business-hour–based replies  
- Personalize replies with sender name  
- Add SLA or priority labels  
- Extend categories for sales, support, or leads  
- Log emails to CRM or Google Sheets  

---

## 🎯 Use Cases

- Online course creators  
- Consultants & coaches  
- Small businesses  
- Customer support teams  
- Agencies managing shared inboxes  

---

## 📌 Notes

- Replies are sent only once per email thread  
- Labels help track and audit AI decisions  
- The workflow is designed to be easily extended  

---

## 📄 License

Free to use and modify.  
You are responsible for your own credentials and data handling.
