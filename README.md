# Academy App - Website Generator Platform

Welcome to **AcademyApp**, a personal project built to help users and small businesses easily create simple websites or landing pages in seconds — without any coding required.

🌐 **Live Demo:** [https://academyapp.click](https://academyapp.click)

---

## 🚀 Project Purpose

This is a solo developer initiative aiming to:

- Provide a **no-code website builder** for users who want a fast online presence.
- Allow users to register/sign in securely with **OTP verification via Twilio**.
- Notify users via **email and SMS** when their website has been successfully generated.

---

## 🔧 Tech Stack

- **Frontend:** HTML, CSS (custom)
- **Backend (in progress):** Golang (Gin / Kratos), PostgreSQL
- **Authentication:** OTP over SMS via Twilio
- **Email Notifications:** Twilio SendGrid
- **Deployment:** AWS EC2, S3

---

## ✉️ Sample Use Case (Twilio)

- User signs up → receives OTP via SMS  
  `“Hi John, your verification code is 398472. It expires in 5 minutes.”`
- After generating a website → receives a notification  
  `“Your site is now live at https://academyapp.click/user/john123.”`

---

## 📌 Current Status

- [x] Domain active at: [https://academyapp.click](https://academyapp.click)  
- [x] HTML landing page available  
- [ ] Backend API integration (in progress)  
- [ ] Twilio integration (pending account reactivation)

---

## 👨‍💻 Author

**Tuyenledev**  
Location: Hanoi, Vietnam  
GitHub: [https://github.com/tuyenledev](https://github.com/tuyenledev)  
Email: [admin@academyapp.click](mailto:admin@academyapp.click)

---

## 🛡️ Disclaimer

This is a personal development project with no malicious intent. SMS and email features will be strictly used for user authentication and system notifications only.
