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