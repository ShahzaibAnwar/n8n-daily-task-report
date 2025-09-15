# n8n-daily-task-report
Automated workflow using n8n that fetches tasks from Airtable, formats them into an Outlook-safe HTML email (with KPIs, color-coded rows, and summaries), and sends it automatically on a schedule (daily/weekly).
# n8n Daily Task Report Workflow  

[![n8n](https://img.shields.io/badge/Built%20with-n8n-1f425f.svg)](https://n8n.io)  
[![Airtable](https://img.shields.io/badge/Data-Airtable-blue)](https://airtable.com)  
![Outlook Safe](https://img.shields.io/badge/Email-Compatible%20with%20Outlook-green)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

---

## 📌 Overview  
This workflow automatically fetches tasks from **Airtable**, compiles them into a **KPI dashboard + color-coded task table**, and sends a **styled HTML email report**.  

✅ Works perfectly in **Gmail and Outlook**  
📊 Shows **KPIs** (Totals, Done, In Progress, Overdue, Due Today, Due Next 7 Days)  
🎨 Adds **color-coded rows** + priority badges  
📅 **Schedules** reports daily, weekly, or at any custom time  

---

## ✨ Features
- **Automated Reporting** – no manual effort needed.  
- **Exec-Friendly View** – KPIs at the top, details in a table.  
- **Outlook Safe** – built with table-based HTML & inline CSS.  
- **Customizable** – easily change recipients, schedule, and formatting.  
- **Priority Highlighting** – “HIGH” tasks get a red pill badge.  

---

## ⚡ How It Works
1. **Schedule Trigger** → sets when report should be sent (default: 9:00 AM).  
2. **Airtable Node** → fetches rows from your selected base/view.  
3. **Code Node** → compiles data into an Outlook-safe HTML email.  
4. **Email Send Node** → delivers report to chosen recipients.  

---

## 🛠 Setup Instructions
1. Clone or import the JSON workflow:  
   ```bash
   git clone https://github.com/ShahzaibAnwar/n8n-daily-task-report.git
