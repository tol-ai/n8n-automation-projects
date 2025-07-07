# Shopify AI Chatbot (n8n + GPT + Webhook)

This project is a working demo of an AI-powered customer support chatbot built using **n8n** and **OpenRouter (ChatGPT-compatible)**. It simulates how a Shopify store can handle common customer inquiries automatically.

---

### 🔧 Features

- Accepts incoming customer messages via webhook (e.g., from chat widget or API)
- Detects intent (order status, FAQs, return requests, etc.)
- Replies with GPT-based responses using mock Shopify data
- Handles 4 customer intents:
  - Order Status
  - FAQ
  - Help
  - Support

---

### 💡 Real-World Job Reference

This demo is based on a real Upwork job post titled:

> **Shopify AI Chatbot Developer**  
> 💰 Budget: $100 – Fixed Price  
> 🎯 Goal: Build an AI chatbot to answer common Shopify store questions like “Where’s my order?”, product returns, and shipping FAQs using ChatGPT and Shopify integration.

---

### 🛠️ Tech Stack Used

- **n8n** (self-hosted)
- **Webhook Trigger**
- **OpenRouter GPT API**
- **Mock Shopify Data** (Order ID, Status, Tracking Number)
- **Node-based Switches & JSON building**

---

### 📁 Project Files

```
chatbot-customer-support/
├── chatbot-workflow.json         # Main n8n workflow
├── test-input.json               # Sample user input for testing
├── project-summary.txt           # Quick description of the project
└── screenshots/                  # Visual preview of the chatbot flow
    ├── 01_order_status.png.jpg
    ├── 02_faq.png.jpg
    ├── 03_help.png.jpg
    └── 04_support.png.jpg
```

---

### 🔍 Notes

- ✅ You can import the `chatbot-workflow.json` directly into n8n
- 🔐 All API keys are removed for security
- 🖼️ Screenshots demonstrate how the bot handles each type of query



