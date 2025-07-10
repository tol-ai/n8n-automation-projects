# 🤖 CRM Onboarding Automation (n8n)

This workflow automates CRM client intake from a webhook form.

---

## 🧠 Use Case

Perfect for sales/marketing teams who collect client leads via forms and want to:

- Save new client data to Airtable automatically
- Notify the team via Gmail
- Log every entry to Google Sheets
- Send success/error response back to the form user

---

## 🛠️ Tech Stack

- 🔗 **n8n**
- 🌐 **Webhook Trigger**
- 🧾 **Airtable API**
- 📊 **Google Sheets API**
- 📧 **Gmail (email alert)**

---

## 📂 Workflow Structure

1. **Receive Webhook** – from a new client form  
2. **Validate Required Fields** – ensure no missing data  
3. **Save to Airtable** – store client info in CRM table  
4. **Send Email Alert** – success or error message  
5. **Log to Google Sheets** – record entry for backup/tracking  
6. **Respond to Sender** – with success or error response

---

## ✅ Sample Output Screenshot

📸 workflow screenshot by Success and workflow screenshot by error

---

## 🧪 Sample Test Input

```json
{
  "firstName": "Juan",
  "lastName": "Dela Cruz",
  "email": "juan@example.com",
  "phone": "09171234567"
}
