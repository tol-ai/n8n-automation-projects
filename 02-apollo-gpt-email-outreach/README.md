# Lead Gen – Apollo > GPT Email > SMTP

This automation fetches cold leads from Apollo (manually or via webhook), filters them, generates personalized messages using GPT, and sends the emails via SMTP.

## 🔁 Workflow Summary

1. 🔍 **Apollo Lead Fetch**
   - Manual or webhook-based lead input (includes name, company, email)

2. 🧹 **Lead Filtering & Validation**
   - Skips leads with missing name/company/email
   - Only continues if valid

3. 🤖 **GPT Cold Email Generation**
   - Creates personalized subject & body using GPT prompt logic

4. 📤 **Email Sending (SMTP)**
   - Sends the generated email using the SMTP node

5. 🗃️ *Optional*: Logs to Airtable or Google Sheets

---

## 📦 Files Included

- `n8n-export.json` – Working n8n flow
- `project-summary.txt` – High-level use case description
- `test-input.json` – Sample Apollo lead format
- `/screenshots` – Screens of workflow & output (add yours)

---

## 🚀 Use Cases

- AI-powered cold outreach
- B2B email campaigns
- Sales automation with Apollo

---

## 🔧 Customize for Clients

- Replace mock Apollo data with API call


- Add logging (e.g., Airtable)
- Customize GPT prompt based on target audience

## 🧠 Use Cases
Automated cold email outreach

B2B lead generation for agencies

Sales development reps (SDRs) using Apollo.io

Startups scaling outbound campaigns

## 🛠️ Tech Stack
n8n – No-code automation platform

GPT (OpenRouter or OpenAI API)

SMTP (Gmail, Outlook, SendGrid, etc.)

## 📁 Files in This Project
File	Description
n8n-export.json	Working export of the n8n workflow
test-input.json	Sample Apollo lead data
project-summary.txt	Short summary of the project
/screenshots/	Visuals of the working flow and output

## 💬 Notes
The base workflow includes GPT logic and email sending.

Apollo API integration can be manual or automated.

For real client projects, lead enrichment, logging, and multiple variations of messaging can be added.

## 🧑‍💻 Author
Archie Cruz / 
AI Automation Developer at Tol.AI
