# Resume-Evaluation-AI-Agent-n8n-Google-Gemini

This repository contains a fully automated solution designed to process incoming resumes via Gmail, extract their content and evaluate them using Google's Gemini AI model — all set up through [n8n.io](https://n8n.io), a powerful low-code automation platform.

This project is ideal for HR teams, recruiters or companies looking to streamline candidate screening using AI.

## Key Features

- 📥 Automatically fetches new resume emails from Gmail.
- 📄 Extracts text from attached PDF resumes.
- 🤖 Evaluates resumes using the Google Gemini AI model for insights like skills, experience and suitability.
- 🔁 End-to-end automation without manual intervention.
- 🛡️ Error handling built-in to manage missing or empty attachments gracefully.
- 🔔 Easily extendable to send notifications, store results or trigger next steps.

## Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **n8n.io** | Workflow automation |
| **Google Gemini API** | AI-based text evaluation |
| **Gmail API** | Reading resume attachments from emails |
| **PDF Extractor** | Reading text content from resumes |

---

## 🏗️ Workflow Structure

1. **Gmail Trigger Node**  
   ➔ Detects new emails with PDF attachments.

2. **Extract Text Node**  
   ➔ Reads and parses PDF file contents.

3. **AI Agent Node (Google Gemini)**  
   ➔ Sends extracted text to Gemini for intelligent evaluation.

4. **Output / Next Steps**  
   ➔ (Customizable) Store evaluations, send Slack/Email notifications, or move candidate profiles into ATS systems.

---

## ⚙️ Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/resume-ai-agent-n8n.git
cd resume-ai-agent-n8n

