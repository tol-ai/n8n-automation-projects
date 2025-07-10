# CRM Onboarding Automation

This workflow automates CRM client intake from a webhook form.

## 🧠 Use Case

Useful for sales/marketing teams who collect client leads from forms and want to auto-save the data into Airtable, notify the team via email, and log the record in Google Sheets.

## 🛠️ Tech Used
- n8n
- Webhook Trigger
- Airtable API
- Google Sheets API
- Gmail (email alert)

## 📂 Workflow Structure

1. Receive Form
2. Validate Data
3. Save to Airtable
4. Send Success/Fail Email
5. Log to Google Sheets
6. Respond back to user

## ✅ Sample Output
(Insert screenshots here)

## 🧪 Test Input
```json
{
  "firstName": "Juan",
  "lastName": "Dela Cruz",
  "email": "juan@example.com",
  "phone": "09171234567"
}
