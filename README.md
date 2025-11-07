# 💌 Automated Email Alert System for Banking Data Analysis (Python)

This project automates the monitoring of key banking KPIs (like loan defaults, customer churn, and high-value transactions) and sends real-time email alerts to stakeholders when unusual patterns or threshold breaches are detected.  
It eliminates manual report checking and enables proactive decision-making in financial analytics.

---

## 🚀 **Project Overview**

Banks and financial institutions handle large amounts of customer and transaction data daily.  
Tracking anomalies or risks (like rising loan defaults or unusually large transactions) manually can be time-consuming and prone to human error.  

This project automates that process using Python. It performs:
- Data cleaning and KPI calculation using **pandas**
- Conditional checks for business rules and risk thresholds
- **Automated email alerts** via Gmail SMTP when metrics exceed defined limits

---

## ⚙️ **Tech Stack**

| Component | Description |
|------------|-------------|
| **Language** | Python 3 |
| **Libraries** | pandas, smtplib, email.mime, python-dotenv |
| **Data Source** | Cleaned banking dataset (`bank_cleaned.csv`) |
| **Visualization** | Power BI (connected to same dataset) |
| **Automation** | Windows Task Scheduler / Cron job |
| **Alerts** | Email via Gmail App Password (SMTP_SSL) |

---

## 🧠 **Key Features**

✅ Automated detection of:
- 📉 High default rates (>10%)  
- 💰 High-value transactions (> ₹1,00,000)  
- 👥 Drop in active customers compared to the previous month  

✅ Real-time email alerts with dynamic HTML content  
✅ Secure credential handling using `.env` or `keyring`  
✅ Ready for scheduling with Task Scheduler (Windows) or cron (Linux/Mac)  
✅ Integrates with Power BI dashboard for visualization consistency  

---

## 🧩 **Project Workflow**

1. **Data Preparation**  
   - Load and preprocess banking data (`bank_cleaned.csv`).  
   - Compute metrics such as default rate, customer activity, and transaction anomalies.

2. **Alert Generation**  
   - Define conditions for triggering alerts (e.g., thresholds for KPIs).  
   - Store messages dynamically in an `alerts` list.

3. **Email Automation**  
   - Format alerts into a professional HTML email.  
   - Send via Gmail SMTP using a secure **App Password**.

4. **Scheduling**  
   - Automate the Python script to run daily/weekly via Task Scheduler or cron.  
   - Log each run for audit and tracking.

---

## 🧰 **Setup Instructions**

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Banking-Email-Alert-Automation.git
cd Banking-Email-Alert-Automation
