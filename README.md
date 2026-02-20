# 📢 Roar2Rest  
### Smart Noise Regulation & Public Transport Complaint Management System

---

## 📌 Overview

**Roar2Rest** is a hybrid mobile application developed using Apache Cordova to monitor vehicle noise violations in restricted zones and manage public transport complaints efficiently.

The system provides three role-based portals:

- 🚗 Driver Portal  
- 👮 Police Portal  
- 🧑 Public Portal  

It ensures real-time noise monitoring, automated fine generation, and centralized complaint management.

---

## 🎯 Problem Statement

Urban cities face:

- Increasing noise pollution in restricted zones  
- Manual fine collection systems  
- Lack of digital monitoring  
- Overcharging and misconduct in public transport  
- No centralized complaint escalation system  

Roar2Rest provides a structured and automated mobile solution.

---

## 🏗 System Modules

### 🚗 Driver Portal
- Secure Login
- Detects entry into noise prohibited zones
- Monitors sound level (dB)
- Alerts driver if threshold exceeded
- Displays fine amount
- Pay Fine Option
- Alternative Route Suggestion
- If unpaid → Case escalated to Police Portal

### 👮 Police Portal
- Secure Login
- View unpaid noise violations
- Access public complaints
- Monitor repeat offenders
- Update case status

### 🧑 Public Portal
- User Registration & Login
- Raise complaints (Overcharging, No change, Misconduct)
- Complaints directly visible in Police Portal
- Track complaint status

---

## ⚙️ Features

- Real-time Noise Monitoring
- Geo-fencing Detection
- Automated Fine Calculation
- Escalation System
- Complaint Management
- Role-Based Authentication
- Administrative Dashboard

---

## 🛠 Technologies Used

- Apache Cordova
- HTML5
- CSS3
- JavaScript
- LocalStorage / Database
- Maps API (for alternative routes)

---

## 📱 Application Workflow

1. Driver enters a noise restricted zone.
2. Sound exceeds allowed dB limit.
3. Alert is generated.
4. Driver can pay fine or ignore.
5. If ignored, case is sent to Police Portal.
6. Public complaints are submitted.
7. Police reviews and updates status.

---

## 🚀 Installation & Setup

Navigate to project folder:

cd roar2rest

Add Android platform:

cordova platform add android

Build the application:

cordova build android

Run the application:

cordova run android

---

## 🔒 Security

- Role-based authentication system
- Secure login validation
- Controlled access to police dashboard
- Complaint and violation tracking
- Case status management

---

## 🔮 Future Enhancements

- IoT-based real-time sound sensor integration
- Online payment gateway integration
- SMS/Email notifications
- Analytics dashboard for authorities
- AI-based noise prediction

---

## 👤 Author

Sridhar R
Full Stack Developer | Data Analyst Enthusiast  
GitHub: https://github.com/sridss07 

---

## 📄 License

This project is developed for academic and learning purposes.
