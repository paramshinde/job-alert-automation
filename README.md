#  Job Alert Automation System (n8n)

An automated workflow that fetches job listings from APIs, filters them based on keywords and target companies, and sends real-time alerts via Telegram.

---

##  Features

* Fetch jobs from public APIs
* Filter jobs based on:

  * Keywords (Python, Backend, ML, etc.)
  * Target companies (JP Morgan, BlackRock, Google, etc.)
* Highlight top companies 
* Send real-time alerts to Telegram
* Scheduled automation using n8n

---

## 🛠 Tech Stack

* n8n (workflow automation)
* Telegram Bot API
* REST APIs (ArbeitNow)
* JavaScript (data processing)

---

##  Workflow

Schedule Trigger → HTTP Request → Split Data → Filter Jobs → Add Priority → Format Message → Telegram Alert

---

##  Example Output

```
 TOP COMPANY

 New Job Alert!

 JP Morgan
 Software Engineer
 https://...
```

---

##  Setup Instructions

1. Import `workflow.json` into n8n
2. Add your Telegram Bot Token
3. Update Chat ID
4. Run or schedule workflow

---

##  Future Improvements

* Avoid duplicate job alerts
* Store jobs in Google Sheets
* Add email notifications
* Multi-platform scraping (LinkedIn, Internshala)
* Dashboard for job tracking

---

## 📌 Author

Param Shinde

---
