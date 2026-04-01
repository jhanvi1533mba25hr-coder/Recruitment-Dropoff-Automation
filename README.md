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
5. Alert sent to recruiter

## 📊 Dashboard Insights
- Total Candidates
- High Risk Candidates
- Risk Distribution
- Roles Applied
- Average Contact Delay

## 📁 Project Structure
