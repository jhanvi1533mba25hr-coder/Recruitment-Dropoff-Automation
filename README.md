# Recruitment Drop-off Automation

## 📌 Project Overview
This project predicts candidate drop-off risk in recruitment process using automation. 
It helps recruiters identify High, Medium, and Low risk candidates and send automated alerts.

## 🚀 Features
- Automated candidate risk prediction
- High / Medium / Low classification
- Recruiter alert emails
- Candidate follow-up emails
- Google Sheets integration
- Power BI dashboard visualization

## 🛠 Tools Used
- n8n (Workflow Automation)
- Google Sheets
- Gmail API
- Power BI
- GitHub

## 🔄 Workflow Explanation
1. Google Sheets Trigger detects new candidate
2. Days since last contact checked
3. Risk level assigned:
   - High (>4 days)
   - Medium (>2 days)
   - Low (<=2 days)
3. Data stored in processed sheet
4. Email sent to candidate
5. Alert sent to recruiter <img width="2000" height="949" alt="image" src="https://github.com/user-attachments/assets/80cec697-14bf-4d2e-b76d-c5d08493367b" />


## 📊 Dashboard Insights
- Total Candidates
- High Risk Candidates
- Risk Distribution
- Roles Applied
- Average Contact Delay<img width="1993" height="983" alt="image" src="https://github.com/user-attachments/assets/43857130-9d73-434b-be63-0321919d29ca" />


## 📁 Project Structure
