# 🌦️ Scheduled Weather Fetcher & Email Notifier

A production-ready **scheduled weather automation** built using **n8n**, which fetches live weather data daily at a fixed time and sends smart, condition-based email alerts to users.

This workflow runs **once every day at 7:00 AM**, retrieves real-time weather data from a public Weather API, evaluates the temperature, and delivers **personalized recommendations** directly to the customer’s email.

---

## 🚀 Project Overview

The **Scheduled Weather Fetcher** is designed to automate daily weather awareness without dashboards, apps, or manual checks.  
At a scheduled time, the system fetches live temperature data, determines whether the weather is **cold or warm**, and sends an email with appropriate suggestions such as wearing a jacket or using sunscreen.

This project demonstrates **real-world automation**, API integration, decision logic, and email delivery using n8n.

---

## ✨ Features

- ⏰ **Daily Scheduled Execution** → Runs automatically once per day at 7 AM  
- 🌐 **Live Weather Data Fetching** → Pulls real-time weather information from an external API  
- 🧠 **Rule-Based Decision Logic** → Uses IF conditions to classify weather type  
- 📧 **Automated Email Alerts** → Sends clear and actionable recommendations to customers  
- 🔄 **Fully Automated** → Zero manual intervention after setup  

---

## 🛠️ Tech Stack

- **Automation Platform:** n8n  
- **Trigger:** Schedule Trigger  
- **API:** Open-Meteo Weather API  
- **Logic:** IF condition node  
- **Notifications:** Gmail / SMTP Email Node  
- **Hosting:** n8n Cloud or Self-Hosted (Docker / VPS)  

---

## 📬 Sample Email Messages

**Cold Weather Alert**  
> “Good morning! The temperature is low today. We recommend wearing a jacket to stay warm.”

**Warm Weather Alert**  
> “Good morning! It’s warm outside today. Please use sunscreen and consider wearing sunglasses.”

---

## ⚙️ Setup Instructions

### Prerequisites
- n8n instance (Cloud or Self-hosted)  
- Internet access for Weather API  
- Gmail or SMTP email credentials  

### Steps
1. Import the workflow JSON into n8n  
2. Configure the Schedule Trigger (7:00 AM)  
3. Set temperature threshold in IF node  
4. Add email credentials  
5. Activate the workflow  

---

## 🔐 Security & Best Practices

- Store API keys securely in n8n credentials  
- Do not hardcode sensitive information  
- Use app passwords for Gmail  
- Enable workflow error handling where needed  

---

## 🔮 Future Enhancements

- AI-based outfit recommendations  
- Location-based dynamic weather fetching  
- Multi-day forecast emails  
- WhatsApp / SMS notifications  
- User preference personalization  

---

## 📧 Contact

Built by **AutomateX** – AI Agent & Automation Agency  

- Email: automatex.sk@gmail.com  
- GitHub: [AutomateX](https://github.com/automatexSK11)  
