# 🚀 Automation Workflows Hub (n8n + AI)

A growing collection of automation workflows built using n8n, AI models, and APIs to solve real-world problems.

This repository documents my journey of building practical automation systems — turning ideas into working solutions.

---

## 📌 Featured Project

### 🧠 Indian Startup Funding Hiring Watchlist

An end-to-end automation workflow that tracks Indian startup funding news and predicts which startups are most likely to start hiring soon.

---

## ⚡ What It Does

- 🔍 Scans 20+ startup and news sources daily  
- 🤖 Uses AI (LLM) to extract structured funding data  
- 📊 Scores startups based on hiring likelihood  
- 📄 Stores results in Google Sheets  
- 📧 Sends a daily email digest of top opportunities  

---

## 🧩 Workflow Architecture

```

Sources → Fetch → Clean HTML → AI Extraction → Explode Articles
→ Filter Recent Data → Enrichment → Hiring Score
→ Google Sheets → Email Digest

```

---

## 🛠️ Tech Stack

- n8n (Workflow Automation)  
- AI / LLM (OpenAI / Gemini)  
- JavaScript (data transformation)  
- Google Sheets API  
- Gmail API  

---

## 🎯 Use Case

Startups often expand their teams after raising funds.

This workflow helps:
- Students  
- Job seekers  
- Developers  

👉 Identify opportunities *before* they are publicly listed.

---

## 📂 Repository Structure

```

.
├── workflows
│   └── startup-funding-watchlist.json
├── assets
│   └── screenshots
└── README.md

```

---

## ⚙️ Setup Instructions

1. Import the workflow JSON into n8n  
2. Add required credentials:
   - Gmail  
   - Google Sheets  
   - LLM (OpenAI / Gemini)  
3. Replace the Google Sheet ID in the workflow  
4. Run the workflow manually for testing  
5. Activate it for daily automation  

---

## 🧪 Example Output

Each execution generates structured data like:

- Startup Name  
- Description  
- Investors  
- Amount Raised  
- Founder LinkedIn  
- Crunchbase Link  
- Hiring Score (High / Likely / Watchlist)  

Stored in Google Sheets and sent via email.

---

## 🚧 Future Plans

- 🔍 Job tracking from startup career pages  
- 📢 Real-time alerts (Telegram / Slack)  
- 📊 Analytics dashboards  
- 🤖 Advanced AI-powered workflows  
- 🌐 Automations using tools beyond n8n  

---

## 💡 Vision

To build systems that:
- Reduce manual effort  
- Provide early insights  
- Help people stay ahead  

---

## 🤝 Contributions & Ideas

Open to ideas, feedback, and collaboration!

---

## 📌 Connect

- LinkedIn: [Aditya Jain](https://www.linkedin.com/in/adddijain/)
- GitHub: [AdityaJain1106](https://github.com/AdityaJain1106/)

---

## ⭐ Support

If you found this useful, consider starring the repo!
