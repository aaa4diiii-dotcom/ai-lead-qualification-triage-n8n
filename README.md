# AI-Powered Lead Qualification & Triage System (n8n)

An enterprise-grade automation workflow built in n8n that captures inbound agency leads, uses LLMs (Gemini) to instantly analyze project descriptions/budgets, logs data to a CRM, and intelligently routes high-value clients to dedicated team channels and tailored email pipelines.

## 🚀 Features
- **Data Standardization:** Custom JavaScript node cleans, sanitizes, and normalizes messy form input fields.
- **AI Triage Engine:** Integrates an advanced AI Agent node running Gemini to dynamically classify leads into "BIG CLIENT" or "SMALL CLIENT" tiers.
- **Parallel Processing:** Splits data into unified rows to alert team channels (Slack) and trigger custom automated email responses simultaneously.

## 📦 How to Use
1. Download the `ai-lead-triage-workflow.json` file from this repository.
2. Import it directly into your n8n instance.
3. Configure your webhook/form trigger and LLM API credentials.
