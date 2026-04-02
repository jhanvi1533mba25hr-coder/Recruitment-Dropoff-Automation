<img width="2000" height="949" alt="image" src="https://github.com/user-attachments/assets/6d7cd916-d4ce-4f55-b280-7fe57a660963" /><img width="2000" height="949" alt="image" src="https://github.com/user-attachments/assets/2a759965-47cf-4268-b53f-1ed34764f5aa" /># Recruitment Drop-off Automation using n8n

## 📌 Project Overview
Recruitment Drop-off Automation is an AI-enabled workflow designed to identify candidates who are at risk of dropping out during the hiring process. The system monitors candidate engagement using Google Sheets data and automatically classifies candidates into High, Medium, and Low risk categories based on the number of days since last contact.

The automation helps recruiters take timely action by sending alerts and follow-up emails, ensuring that potential candidates are not lost due to delayed communication. This project improves recruitment efficiency and reduces manual tracking.

---

## 🎯 Problem Statement
In recruitment processes, many candidates drop off due to:
- Delayed recruiter communication
- Lack of follow-ups
- Poor tracking of candidate engagement
- Manual monitoring inefficiencies
- No risk prediction mechanism

This leads to:
- Increased hiring time
- Loss of qualified candidates
- Higher recruitment costs
- Poor candidate experience

---

## 🚀 Solution
This project automates candidate tracking and:
- Predicts drop-off risk
- Classifies candidates
- Sends automated follow-ups
- Alerts recruiter
- Stores processed data
- Visualizes insights in dashboard

---

## 🛠 Tools & Technologies Used
- n8n (Workflow Automation)
- Google Sheets 
- Gmail Automation
- Power BI Dashboard
- GitHub Repository

---

## 📊 Dataset Preview
<img width="2000" height="1125" alt="image" src="https://github.com/user-attachments/assets/f2205ac7-ab39-43e4-98be-67a8df7846df" />



## 🔄 Workflow Explanation
1. Google Sheets Trigger monitors new candidate entries
2. System reads "Days Since Last Contact"
3. If condition checks candidate inactivity
4. Risk Level assigned:
   - High Risk (>4 days)
   - Medium Risk (>2 days)
   - Low Risk (<=2 days)
5. Risk Level added to data
6. Data merged and stored in processed sheet
7. Follow-up email sent to candidate
8. Alert email sent to recruiter
9. Dashboard updated with insights
10.  <img width="2000" height="949" alt="image" src="https://github.com/user-attachments/assets/64f2b4d1-efb4-4469-8c16-9a263635daba" />

---

## ⚙️ Risk Classification Logic
| Days Since Last Contact | Risk Level |
|-------------------------|------------|
| 0-2 Days                | Low        |
| 3-4 Days                | Medium     |
| >4 Days                 | High       |

---

## 📊 Dashboard Insights
The Power BI dashboard provides:
- Total Candidates
- High Risk Candidates
- Medium Risk Candidates
- Low Risk Candidates
- Risk Distribution Chart
- Roles Applied Distribution
- Average Contact Delay
- Location-wise Candidates
- <img width="1993" height="983" alt="image" src="https://github.com/user-attachments/assets/464bd423-b9da-4b4e-99d5-5bd5fb13b83d" />

---

## 📁 Project Structure


---

## 🎯 Key Features
- Automated candidate tracking
- Risk prediction logic
- Real-time recruiter alerts
- Candidate follow-up emails
- Google Sheets integration
- Dashboard analytics
- No manual intervention
- Low-code automation

---

## 💡 Benefits of the Project
- Reduces candidate drop-offs
- Improves recruiter response time
- Enhances candidate experience
- Automates follow-up process
- Saves recruiter effort
- Data-driven hiring decisions
- Improves hiring efficiency
- Reduces hiring cycle time
- Centralized candidate tracking

---

## 📈 Future Scope
- AI-based resume scoring
- Machine learning risk prediction
- WhatsApp notification integration
- ATS system integration
- Interview scheduling automation
- Candidate chatbot integration
- Email sentiment analysis
- Real-time analytics dashboard
- Multi-role hiring automation
- Predictive hiring insights

---

## 🔍 Use Case
This system can be used by:
- HR Teams
- Recruitment Agencies
- Startups
- Corporate Hiring Teams
- BPO Hiring Teams
- Campus Recruitment Teams

---

## 📧 Email Automation
Two types of emails are triggered:
1. Candidate Follow-up Email
2. Recruiter Risk Alert Email

This ensures both parties stay informed.

---

## 📊 Business Impact
- Reduced drop-off rate
- Faster hiring
- Improved recruiter productivity
- Better candidate engagement
- Data-backed recruitment strategy

---

## 👩‍💻 Author
Jhanvi Sabharwal  
MBA HR | AI in Recruitment Project  
