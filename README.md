# Automation workflow Data Collection By n8n 

An automated AI-powered workflow built using **n8n** to collect, clean, and structure data from multiple sources.  
The agent runs on a scheduled basis and stores all processed data in Google Sheets for further analysis.

---

## 🚀 Overview
This workflow automates the full data collection pipeline:
- Fetches data from multiple APIs and web sources
- Cleans and normalizes the data
- Stores results in a structured Google Sheet

---

## ✨ Key Features
- Multi-source data extraction  
- AI-based classification & enrichment  
- Error handling + retry logic  
- Automatic daily execution  
- Clean JSON → Sheet mapping  

---

## 🧠 Workflow Logic
1. Trigger (Cron)  
2. API Fetch (multiple endpoints)  
3. Data cleaning & formatting  
4. Save to Google Sheets  
5. Logging & notifications  

---

## 🛠 Tech Stack
- n8n  
- Google Sheets API  
- HTTP Request
- JSON processing  

---

## 📂 Folder Structure
/assets
/workflow.json

---
## ⚙️ Setup
1. Import `workflow.json` into n8n  
2. Add API keys (OpenAI, Google)  
3. Configure Google Sheets credentials  
4. Activate Cron trigger  

---

## 👤 Author
Omar Sahhari  
AI Automation & Intelligent Systems

