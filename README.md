# Dormant Account Reactivation Demo

An interactive proof-of-concept demo for **Stanbic Bank Zambia** built by **Unzima Technologies**.

This demo showcases a modern automated solution that helps banks drastically reduce manual phone calls to customers with dormant or inactive accounts through **SMS notifications** and a comprehensive **USSD self-service menu**.

---

## 🎯 Project Overview

Banks in Zambia currently face the challenge of manually contacting hundreds or thousands of customers monthly whose accounts have become dormant due to inactivity.

This demo demonstrates how Unzima Technologies solves this pain point with:
- Automated SMS notifications
- A realistic multi-step USSD menu (*456#)
- Mobile Money deposit integration (MTN MoMo & Airtel Money)
- Secure OTP verification for account reactivation
- Self-service account deactivation

**Goal**: Faster account reactivation, significant reduction in operational costs, and improved customer convenience.

---

## ✨ Live Demo

**Try the interactive demo here:**  
[https://unzimatechnologies.github.io/dormant-account-demo/](https://unzimatechnologies.github.io/dormant-account-demo/)

---

## 📱 Demo Features

### Bank Admin Dashboard
- View list of detected dormant and inactive accounts
- Send bulk SMS notifications to all inactive customers
- Send individual SMS to specific accounts

### Customer Experience Simulator
- Realistic SMS notification preview
- Full interactive **USSD menu (*456#)** with the following options:

  1. **Check Account Status**  
     → Opens a second layer showing:
     - 1. Inactive
     - 2. Dormant

  2. **Reactivate Account** (Recommended)  
     → **Multi-step secure flow**:
     - System sends a simulated 6-digit OTP
     - User enters the OTP code
     - Upon successful verification, user receives a final confirmation SMS:
       > ✅ Success  
       > Dear Customer, your Stanbic Bank account ending ****4821 has been successfully reactivated.

  3. **Deposit via Mobile Money**  
     → Shows sub-options:
     - MTN Mobile Money
     - Airtel Mobile Money

  4. **Deactivate Account**

- Clean, professional Stanbic Bank branding
- Fully responsive design (works great on mobile devices)

---

## 🛠️ Technologies Used

- HTML5 + Tailwind CSS (via CDN)
- Vanilla JavaScript
- Font Awesome Icons
- Fully client-side (no backend required for this demo)

**Note**: This is a **frontend-only demonstration**.  
The production version will include:
- Real SMS gateway integration
- Dedicated USSD short code
- MTN MoMo & Airtel Money API integration
- Secure backend with real OTP generation and validation
- Core banking system integration
- Full security and compliance features

---

## 📄 License

This demo is protected under the **Unzima Technologies End User License Agreement (EULA)**.

- This is an **evaluation/demo version only**.
- Commercial use, production deployment, or redistribution is **strictly prohibited** without a proper license from Unzima Technologies.
- See [`LICENSE.md`](LICENSE.md) for full terms.

---

## 🚀 How to Run Locally

1. Clone or download this repository
2. Open the `index.html` file in any modern web browser (Chrome, Edge, or Firefox recommended)
3. No installation or server required

---

## 📋 Production Roadmap

| Phase              | Features                                           | Estimated Timeline |
|--------------------|----------------------------------------------------|--------------------|
| Demo (Current)     | Interactive prototype with enhanced multi-step USSD flow | Completed          |
| MVP                | Real SMS + USSD + OTP + Mobile Money integration   | 4–6 weeks          |
| Integration        | Core banking system + security & compliance        | 2–3 weeks          |
| Go-Live            | Full deployment, training & monitoring             | 1–2 weeks          |

---

## 👥 About Unzima Technologies

Unzima Technologies is a Zambian technology company specializing in innovative fintech and digital solutions for banks and financial institutions.

We build practical, scalable systems that solve real business challenges in the Zambian market — including USSD platforms, mobile money integrations, and automated banking workflows.

**Contact:**
- Email: 
- Phone: 
- Location: Lusaka, Zambia

---

## ⚠️ Important Notice

This is a **demonstration only**.  
All data, SMS messages, USSD flows, OTP codes, and transactions shown are **simulated** for presentation purposes.

For a customized live demo, detailed proposal, or full production implementation, please contact Unzima Technologies.

---

**Made with ❤️ in Zambia for Zambian Banks**

---
