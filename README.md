# 🚀 ShortConverter AI Automation

An end-to-end AI-powered automation system built with **n8n** that generates SEO-optimized content, publishes articles to ShortConverter, creates Pinterest marketing assets, and automatically distributes content across multiple platforms with minimal human intervention. The workflow combines AI content generation, humanization, API integrations, and social media automation into a single scalable pipeline. :contentReference[oaicite:0]{index=0} :contentReference[oaicite:1]{index=1}

---

## ✨ Features

- 🤖 AI-powered SEO article generation
- 📝 AI content humanization
- 📈 Automatic SEO metadata generation
- 🌐 Direct publishing to ShortConverter via API
- 📌 Automatic Pinterest content generation
- 🖼️ AI-generated Pinterest images
- 🚀 Automatic publishing of multiple Pinterest pins
- 📊 Google Sheets integration for content management
- 📧 Email notifications after successful execution
- ⚡ Fully automated end-to-end workflow

---

## 🛠️ Tech Stack

- n8n
- Qwen AI
- Google Sheets
- HTTP API
- Pinterest API
- Gmail
- JSON
- JavaScript

---

## 📋 Workflow Overview

1. Read pending topics from Google Sheets.
2. Validate workflow conditions.
3. Generate a fully SEO-optimized article using AI.
4. Parse and structure the AI response.
5. Humanize the generated content.
6. Publish the article to the ShortConverter website.
7. Update the Google Sheet with the published URL and status.
8. Generate Pinterest titles, descriptions, hashtags, and image prompts.
9. Create Pinterest graphics.
10. Publish three Pinterest pins automatically.
11. Send a completion email.

---

## 📂 Project Structure

```
Google Sheets
      │
      ▼
Article Generation (Qwen AI)
      │
      ▼
Content Parsing
      │
      ▼
Humanizer
      │
      ▼
Publish to ShortConverter API
      │
      ▼
Update Google Sheet
      │
      ▼
Generate Pinterest Content
      │
      ▼
Generate Images
      │
      ▼
Publish Pinterest Pins
      │
      ▼
Email Notification
```

---

## 🔑 Requirements

- n8n
- Qwen API Key
- Google Sheets Credentials
- Pinterest API Credentials
- Gmail Credentials
- ShortConverter API Access

---

## 🚀 Installation

1. Clone this repository.

```bash
git clone https://github.com/yourusername/shortconverter-ai-automation.git
```

2. Import the workflow JSON into n8n.

3. Configure all credentials.

4. Update API endpoints and environment variables.

5. Execute the workflow.

---

## 📌 Use Cases

- Automated blogging
- AI content generation
- SEO automation
- Pinterest marketing
- Content publishing
- Affiliate websites
- File converter websites
- Marketing automation

---

## 📄 License

This project is provided for educational and personal use. Modify and extend it according to your requirements.

---

## 👨‍💻 Author

**Asadullah**

AI Engineer • n8n Automation Expert • AI Agent Developer
