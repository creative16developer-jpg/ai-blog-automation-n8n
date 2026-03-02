# 🤖 AI Blog Automation System (n8n + WordPress)

An automated AI-powered content publishing system that generates SEO-optimized blog posts and publishes them directly to WordPress.

This workflow pulls keywords from Google Sheets, generates blog content using an LLM API, publishes via WordPress REST API, and updates the sheet status automatically.

---

## 🚀 Features

- ✅ AI-generated SEO blog content
- ✅ Auto-publish to WordPress
- ✅ Google Sheets integration
- ✅ Status-based duplicate prevention
- ✅ Scheduled execution (cron-based)
- ✅ Docker-based local deployment

---

## 🧠 Workflow Architecture

Google Sheets → n8n → AI API → WordPress → Google Sheets Update

---

## ⚙️ Tech Stack

- n8n (Workflow Automation)
- WordPress REST API
- Google Sheets API
- OpenRouter (LLM API)
- Docker

---

## 🔄 How It Works

1. User adds a keyword in Google Sheets with status `pending`
2. n8n checks the sheet every minute
3. AI generates SEO-optimized content
4. WordPress post is created automatically
5. Google Sheet status updates to `published`

---

## 📌 Example Sheet Format

| keyword | status |
|----------|--------|
| AI tools for SEO | pending |

---

## 🛠 Setup Instructions

1. Import the workflow JSON into n8n
2. Configure:
   - Google Sheets credentials
   - WordPress Application Password
   - OpenRouter API key
3. Activate the workflow
4. Add keywords with status `pending`

---

## 📈 Use Cases

- SEO Agencies
- Content Marketing Teams
- Blogging Automation
- AI Content Scaling
- WordPress Automation

---

## 📬 Author

Developed by [Your Name]
