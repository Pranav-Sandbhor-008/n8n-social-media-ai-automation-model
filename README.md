# 🚀 Social Media Content Automation Workflow

Automate the creation, optimization, and publishing of social media content using **AI-powered workflows**, **Google Sheets**, and **social media APIs**.  
This project transforms raw articles into platform-specific posts and publishes them automatically to **LinkedIn** and **X (Twitter)**.

---

## 📌 Overview

Managing content across multiple platforms is time-consuming. This workflow solves that by:

- Listening for content updates from **Google Sheets**
- Summarizing long-form articles using **Large Language Models (LLMs)**
- Generating optimized posts for different social platforms
- Automatically publishing posts with zero manual effort

---

## 🧠 Workflow Architecture

1. **Google Sheets Trigger**
   - Detects new or updated rows containing article content or links

2. **AI Article Summarization**
   - Uses LLMs to convert long articles into concise summaries

3. **Content Generation**
   - Creates platform-specific posts:
     - Professional tone for LinkedIn
     - Short, engaging format for X (Twitter)

4. **Automated Publishing**
   - Posts content directly to social media platforms

---

## ✨ Features

- 📊 Google Sheets–driven content pipeline  
- 🤖 AI-powered summarization and content generation  
- ✍️ Platform-specific writing styles  
- 🔗 LinkedIn & X (Twitter) auto-posting  
- ⚡ Scalable and fully automated workflow  

---

## 🛠 Tech Stack

- **Automation Platform** (visual workflow editor)
- **Google Sheets API**
- **Google Gemini (LLM)**
- **LinkedIn API**
- **X (Twitter) API**

---

## 📂 Project Structure

```bash
├── workflow/
│   ├── google-sheets-trigger
│   ├── summarize-articles
│   ├── generate-linkedin-post
│   ├── generate-x-post
│   └── publish-posts
├── assets/
│   └── workflow-diagram.png
├── README.md
