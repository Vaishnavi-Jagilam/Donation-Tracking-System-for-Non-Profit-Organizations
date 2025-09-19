# Donation-Tracking-System-for-Non-Profit-Organizations
📝 Description  The Donation Tracking System in Salesforce is a cloud-based solution for NGOs and charitable organizations to manage and monitor donations efficiently. It provides a public donor portal where individuals can:  Donate money securely for different causes (Orphanages, Old Age Homes, Helping Poor).  
# 🏥 Donation Tracking System in Salesforce

## 📌 Project Overview
The **Donation Tracking System** is a Salesforce-based solution designed for NGOs and charitable organizations.  
It provides a **portal for donors** to contribute to various causes (Orphanages, Old Age Homes, Helping Poor, Blood Donation, Clothes/Item donations) while enabling **NGO staff** to manage, track, and report on donations efficiently.

This system is built on **Salesforce Experience Cloud, Custom Objects, and Automation** to ensure seamless donor experience and transparent donation management.

---

## 🎯 Objectives
- Provide a **public portal** where donors can:
  - Donate money online.
  - Register as blood donors.
  - Pledge clothes and essential items.
  - Track the status of their donations (like order tracking).

- Enable **NGO staff** to:
  - Manage donation campaigns.
  - Update donation statuses.
  - Generate automated receipts & thank-you emails.
  - View dashboards for campaign progress and donor engagement.

---

## 🚀 Features
### Donor Portal (Experience Cloud)
- 💳 **Monetary Donations** – online payments with tracking (Pledged → Processing → Received → Receipt Sent).
- 🩸 **Blood Donations** – donor registration with details (Name, Blood Group, City, Availability).
- 👕 **Clothes/Item Donations** – pledge items with delivery/pickup options and tracking (Pledged → Collected → Distributed).
- 📜 **Donation Tracking** – donors can see donation history and statuses.
- 📧 **Receipts & Emails** – donors receive thank-you emails with tax receipts.

### NGO Staff (Salesforce Internal Users)
- Manage **Campaigns** (Orphanages, Old Age Homes, Poor, Blood Drives).
- View & update **Donation records**.
- Access **Blood donor lists** by blood group & city.
- Generate **Reports & Dashboards** for:
  - Donations by cause
  - Top donors
  - Campaign progress
  - Blood donor availability

---

## 🏗️ System Architecture
1. **Donor (Portal User)** → fills donation/blood/item form.
2. **Experience Cloud Portal** → submits record into Salesforce.
3. **Salesforce Backend**:
   - Objects: `Donation__c`, `Blood_Donor__c`, `Item_Donation__c`, `Campaign`, `Contact`.
   - Automations: Flows, Validation Rules, Email Alerts, PDF Receipts.
4. **Donation Tracking**:
   - Donors → Portal → See donation status.
   - Staff → Salesforce → Manage data & reports.

---

## 📂 Data Model
- **Donation__c** → Tracks monetary donations.
- **Blood_Donor__c** → Registers blood donors.
- **Item_Donation__c** → Tracks pledged goods (clothes, items).
- **Campaign (Standard)** → Represents donation causes.
- **Contact (Standard)** → Donor details.

---

## ⚡ Automation
- **Thank You Email & Receipt** → Triggered when donation is received.
- **Campaign Progress Updates** → Roll-up donations against goals.
- **Blood Donor Notifications** → Alerts NGO staff when new blood donor registers.
- **Clothes Donation Tracking** → Updates status when collected/distributed.

---

## 📊 Reports & Dashboards
- Donations by Campaign (Orphanages, Old Age Homes, Poor).
- Top Donors.
- Campaign Progress (Goal vs Raised).
- Blood Donors by City & Blood Group.
- Clothes Donations by Status.

---

## 🛠️ Tech Stack
- **Salesforce Platform**
- **Experience Cloud** (for portal)
- **Flows & Validation Rules** (automation)
- **Visualforce** (for PDF receipts)
- **Reports & Dashboards**

---

## 📌 Future Enhancements
- Integration with **payment gateways** (Stripe, Razorpay, PayPal).
- Mobile-first portal for donors.
- AI-powered donor engagement (predict recurring donations).

---

## 👨‍💻 Contributors
- **Project Lead & Developer:** [Your Name]
- **Mentor/Guide:** [Guide/Professor Name, if applicable]

---

## 📜 License
This project is licensed under the MIT License - feel free to use and extend it.

