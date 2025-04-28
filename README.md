# Resume-Evaluation-AI-Agent-n8n-Google-Gemini

## Problem Statement

Recruiters and HR teams often receive hundreds of resumes via email, making it difficult, time-consuming and error-prone to manually screen and evaluate each candidate. Traditional resume screening methods are manual, inconsistent and can miss highly qualified candidates due to human fatigue or oversight. There is a growing need for an automated, intelligent and scalable way to analyze resumes as soon as they are received — helping organizations make faster, more accurate hiring decisions.

This repository contains a fully automated solution designed to process incoming resumes via Gmail, extract their content and evaluate them using Google's Gemini AI model — all set up through [n8n.io](https://n8n.io), a powerful low-code automation platform. This project is ideal for HR teams, recruiters or companies looking to streamline candidate screening using AI.

## Key Features

📥 Automatically fetches new resume emails from Gmail.
📄 Extracts text from attached PDF resumes.
🤖 Evaluates resumes using the Google Gemini AI model for insights like skills, experience and suitability.
🔁 End-to-end automation without manual intervention.
🛡️ Error handling built-in to manage missing or empty attachments gracefully.
🔔 Easily extendable to send notifications store results or trigger next steps.

## Tech Stack

| Technology | Purpose |
| :--- | :--- |
| **n8n.io** | Workflow automation |
| **Google Gemini API** | AI-based text evaluation |
| **Gmail API** | Reading resume attachments from emails |
| **PDF Extractor** | Reading text content from resumes |
| **Google Sheets** | Storing data in google sheets |


## Workflow Structure

1. **Gmail Trigger Node**  
   ➔ Detects new emails with PDF attachments.

2. **Extract Text Node**  
   ➔ Reads and parses PDF file contents.

3. **AI Agent Node (Google Gemini)**  
   ➔ Sends extracted text to Gemini for intelligent evaluation.

4. **Output / Next Steps**  
   ➔ (Customizable) Store evaluations, send Slack/Email notifications or move candidate profiles into ATS systems.
   
    <img width="911" alt="image" src="https://github.com/user-attachments/assets/c135b53e-46df-45a6-a41f-5985966d5b6e" />

## How This Project Helps

- Real-time Resume Processing: As soon as resumes arrive, they are evaluated automatically.
- AI-Based Candidate Insights: Identify skills, experience levels and suitability based on custom prompts.
- Time Savings: Reduces manual resume screening time by over 80%.
- Improved Accuracy: AI ensures that qualified candidates are not missed.
- Scalability: Can handle hundreds or thousands of resumes without human fatigue.
- Easy Integration: Can be expanded into ATS (Applicant Tracking Systems) or recruitment CRMs.

## Where You Can Use This
- Startup hiring
- Corporate HR teams
- Recruitment agencies
- Freelance recruiters
- Educational institutions (for campus placements)

- Contributing - Feel free to submit pull requests, open issues or suggest features!
