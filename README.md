
# 🚀 Automation Workflows Hub (n8n + AI)

A growing collection of real-world automation workflows built using **n8n, AI models, and APIs**.

This repository documents my journey of building systems that **eliminate repetitive work, enhance decision-making, and automate end-to-end processes.**

---

## 📌 Featured Projects

### 🧠 Indian Startup Funding Hiring Watchlist
An automation workflow that tracks startup funding news and predicts which startups are likely to hire soon.

### 🤖 ATS Resume Optimizer — AI Job Application Automation
An end-to-end workflow that automatically generates **ATS-optimized, tailored resumes** for real job listings every day.

---

## ⚡ What These Workflows Do

### 🧠 Hiring Watchlist
- 🔍 Scans 20+ startup/news sources daily  
- 🤖 Extracts structured funding data using AI  
- 📊 Scores startups based on hiring likelihood  
- 📄 Stores insights in Google Sheets  
- 📧 Sends daily email digest  

---

### 🤖 ATS Resume Optimizer
- 🔍 Scrapes fresh LinkedIn job listings daily (via Apify)  
- 📄 Fetches base resume from Google Drive  
- 🤖 Uses AI (Google Gemini) to tailor resumes for each job  
- 📑 Auto-generates a new resume (Google Docs) per role  
- 📧 Sends daily email with ready-to-apply resumes + links  

💡 **Result:** Zero manual effort → Just review & apply.

---

## 🧩 Workflow Architecture

### 🧠 Hiring Watchlist
```

Sources → Fetch → Clean HTML → AI Extraction → Explode Articles
→ Filter Recent Data → Enrichment → Hiring Score
→ Google Sheets → Email Digest

```

### 🤖 ATS Resume Optimizer
```

LinkedIn Jobs → Apify Scraper → Resume Fetch (Drive)
→ AI Tailoring (Gemini) → Generate Docs
→ Store Links → Email Digest

```

---

## 🛠️ Tech Stack

- **n8n** (Workflow Automation)  
- **AI / LLMs** (Google Gemini, OpenAI)  
- **JavaScript** (data transformation)  
- **Google Docs API**  
- **Google Drive API**  
- **Google Sheets API**  
- **Gmail API**  
- **Apify** (Web scraping)  

---

## 🎯 Use Cases

### 🧠 Hiring Watchlist
Helps:
- Students  
- Job seekers  
- Developers  

👉 Discover opportunities *before they are publicly visible*

---

### 🤖 ATS Resume Optimizer
Helps:
- Job seekers  
- Developers  
- Anyone applying to multiple roles  

👉 Apply smarter with **personalized, ATS-friendly resumes at scale**

---

## 📂 Repository Structure

```

.
├── workflows
│   ├── startup-funding-watchlist.json
│   └── ats-resume-optimizer.json
├── assets
│   └── screenshots
└── README.md

```

---

## ⚙️ Setup Instructions

1. Import the workflow JSON into n8n  
2. Configure credentials:
   - Gmail  
   - Google Drive / Docs / Sheets  
   - LLM (OpenAI / Gemini)  
   - Apify API  
3. Update IDs (Google Docs / Sheets / Drive)  
4. Run workflow manually for testing  
5. Enable scheduled triggers  

---

## 🧪 Example Outputs

### 🧠 Hiring Watchlist
- Startup Name  
- Funding Details  
- Investors  
- Hiring Score (High / Likely / Watchlist)  

---

### 🤖 ATS Resume Optimizer
- Tailored Resume (Google Docs link)  
- Job Role & Company  
- Direct Apply Link  
- Daily Email Digest  

---

## 🚧 Future Plans

- 🤖 Full job application autopilot (auto-apply workflows)  
- 📢 Real-time alerts (Telegram / Slack / WhatsApp)  
- 📊 Dashboards & analytics layer  
- 🧠 Smarter AI scoring & personalization  
- 🌐 Multi-platform job scraping (LinkedIn, Indeed, etc.)  

---

## 💡 Vision

To build automation systems that:
- Eliminate repetitive manual work  
- Provide intelligent insights  
- Help people **move faster and smarter**

---

## 🤝 Contributions & Ideas

Open to ideas, feedback, and collaboration!

---

## 📌 Connect

- LinkedIn: https://www.linkedin.com/in/adddijain/  
- GitHub: https://github.com/AdityaJain1106  

---

## ⭐ Support

If you found this useful, consider starring the repo ⭐
```

