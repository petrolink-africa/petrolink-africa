# PetroLink Africa – Automation Deployment SOP  
**Version 1.0** | Last Updated: August 3, 2025

---

## 🚀 Live Preview  
[https://petrolink-africa.github.io/petrolink-africa](https://petrolink-africa.github.io/petrolink-africa)
---

## 📁 Folder Structure

---

## Welcome  
Hi **[Freelancer Name]**,welcome aboard! This SOP will guide you through deploying PetroLink Africa’s launch assets with zero confusion. Follow each step carefully, and reach out if anything’s unclear. Let’s make this rollout flawless.

---

## Table of Contents  
1. Overview & Objectives  
2. Google Drive Folder Setup  
3. GitHub Deployment  
4. Zapier & Twilio Flows  
5. WhatsApp & Email Templates  
6. Known Issues & Fixes  
7. Version History & Future Updates  
8. Handoff Confirmation Checklist  

---

## 1. Overview & Objectives  
PetroLink Africa’s goal is to launch a fully automated, zero-staff B2B platform. This SOP centralizes all steps and assets to ensure consistency, speed, and reliability during deployment.

---

## 2. Google Drive Folder Setup  
1. Create main folder: `PetroLink_Onboarding_Kit`  
2. Create subfolders:  
   - `GitHub_Deployment_Instructions/`  
   - `Investor_Announcement/`  
   - `Assets/`  
   - `Completed_Checklists/`  
3. Place files as follows:  
   - **Assets/**: `setup.exe`, logo, banner, QR codes  
   - **GitHub_Deployment_Instructions/**: `ENGLISH.md`, `FRENCH.md`, etc.  
   - **Investor_Announcement/**: email, WhatsApp, LinkedIn templates  

---

## 3. GitHub Deployment  
1. Clone repo:  
   ```bash
git clone https://github.com/petrolink-africa/petrolink-africa.git
   cd petrolink-africa
   
   git add .
git commit -m "Add launch assets"
git push origin main


And continue with the rest of the SOP sections (Zapier, WhatsApp, checklist, footer, etc.).

---

## 4. Zapier & Twilio Flows
PetroLink Africa uses Zapier and Twilio to automate RFQ responses and buyer onboarding.

🔧 Zapier Setup
Log into Zapier

Import the shared Zap: PetroLink_RFQ_AutoResponder

Connect Google Sheets and WhatsApp API

Test trigger: new row in RFQ_Log sheet

Confirm WhatsApp message is sent with buyer name and RFQ summary

📞 Twilio Setup
Log into Twilio Console

Create messaging service: PetroLink_AutoReply

Link to WhatsApp number

Set fallback SMS template

Test with sandbox number

5. WhatsApp & Email Templates
Use these templates for investor and buyer outreach.

📱 WhatsApp Template
text
Hi [Name],  
PetroLink Africa is now live! 🚀  
Explore our automated B2B platform: [Live Link]  
Need help? Just reply here.
📧 Email Template
Subject: PetroLink Africa is Live – Explore the Future of B2B Petroleum Trading Body: Dear [Name], We’re thrilled to announce the launch of PetroLink Africa – a fully automated, zero-staff B2B platform. Visit: [Live Link] Best regards, The PetroLink Team

6. Known Issues & Fixes
Issue	Fix
GitHub pages not updating	Clear cache and re-push with git commit --amend
WhatsApp message not sending	Check Twilio sandbox expiration
Zapier not triggering	Ensure Google Sheets is correctly linked and shared
7. Version History & Future Updates
v1.0 – August 3, 2025 Initial SOP release with GitHub, Zapier, Twilio, and onboarding templates.

Next Update:

Add multilingual onboarding videos

Integrate CRM auto-tagging

8. Handoff Confirmation Checklist
✅ GitHub repo cloned and deployed ✅ Google Drive folders created and populated ✅ Zapier and Twilio flows tested ✅ WhatsApp and email templates customized ✅ README.md updated and committed ✅ Freelancer walkthrough completed

📬 Footer
For questions or support, contact: 📧 support@petrolink.africa 📱 WhatsApp: +233-XXX-XXX-XXX

-----

## 🔄 Final Step

Once pasted:
1. Scroll down in GitHub
2. Add a commit message like:  
   `Added full SOP to README.md`
3. Click **Commit changes**

---


   git clone https://github.com/petrolink-africa/petrolink-africa.git
   cd petrolink-africa
