# n8n-daily-task-report
Automated workflow using n8n that fetches tasks from Airtable, formats them into an Outlook-safe HTML email (with KPIs, color-coded rows, and summaries), and sends it automatically on a schedule (daily/weekly).
# n8n Daily Task Report Workflow

This repository contains an **n8n workflow** that automatically pulls tasks from Airtable, compiles KPIs, and sends a **styled HTML email report**.  
The email is **Outlook-safe** (table-based, inline CSS) and includes:

- 📊 KPI summary (Total, Completed, In Progress, Overdue, Due Today, Due Next 7 Days)  
- ✅ Color-coded rows (Done = green, In Progress = orange, Overdue = red)  
- 🔴 Priority badges (HIGH)  
- 📅 Nicely formatted dates  
- 📨 Auto-email scheduling (daily, weekly, or custom)  

---

## 🚀 How it Works
1. **Schedule Trigger** – set when the report should be sent (e.g., 9:00 AM daily).  
2. **Airtable Node** – fetches tasks from your Airtable base/view.  
3. **Code Node** – compiles and formats the tasks into an Outlook-safe HTML email.  
4. **Email Send Node** – sends the report to chosen recipients.  

---

## 🛠 Setup
1. Clone this repo or import the JSON workflow into your n8n instance.  
2. Connect your **Airtable** and **Email (SMTP/Gmail/Outlook)** credentials.  
3. Update Airtable Base/Table/View in the workflow.  
4. Adjust the schedule (default: 9:00 AM).  
5. Update the "To Email" field in the Email node.  
6. Test run once → you’ll see the formatted email in your inbox.  

---

## 📌 Example Email Preview
- CEO-friendly KPI dashboard at the top.  
- Task list table with assignee, due date, and summary.  
- Color-coded rows and legend for easy scanning.  

---

## 📜 License
MIT License – feel free to use and adapt.  

---

### JSON Workflow
The exported workflow file is available here:  
`MY Work Status Email copy.json`

---

✅ This makes your GitHub repo ready to be linked in your CV, LinkedIn, or when submitting to **n8n Templates**.

---

👉 Do you want me to also create a **fancy README with badges (n8n, Airtable, Outlook-safe, MIT License)** so it looks more like a polished open-source project?

