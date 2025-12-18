# Ai-fertilizer-shop-order-automation  🔹 AI-Powered Fertilizer Shop Order Automation
📌 Overview

This project is an AI-driven order automation system built using n8n, OpenAI, and Airtable for a fertilizer shop.

It enables:

Instant order confirmation to customers

Automatic order notification to the shop owner

Structured data storage in Airtable

Conversational AI interaction for order handling

This workflow is designed to reduce manual work, improve response time, and ensure reliable order processing.

⚙️ Tech Stack

n8n – Automation orchestration

OpenAI (GPT-4.1-mini) – Conversational AI agent

Airtable – Order & product data storage

Email (SMTP / n8n Email Node) – Owner notifications

🔁 Workflow Logic (High Level)

Customer sends an order message

AI Agent understands the order

Airtable is queried for product data

Order is confirmed to the customer instantly

Order details are emailed to the shop owner

Airtable records are updated automatically

🧠 AI Capabilities

Natural language order understanding

Context memory for conversation continuity

Structured data extraction for Airtable

Error-resistant order handling

📂 Files Included
workflow/
 └── fertilizer-shop-n8n-workflow.json   → Import directly into n8n

🚀 How to Use

Clone this repository

Import the workflow JSON into n8n

Add your credentials:

OpenAI API key

Airtable Personal Access Token

Email (SMTP)

Activate the workflow

Start receiving orders automatically

🔐 Security Notes

API keys and credentials are NOT included

Use environment variables or n8n credentials

📈 Future Improvements

WhatsApp order confirmation

Payment integration

Admin dashboard

Multi-language support

👤 Author

Built by [Usman Farooq]
AI Automation & Workflow Engineer
