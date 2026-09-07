# 📌 Placement Management System

A full-stack MERN project for managing the college placement process, including:

* Student application tracking
* Interview scheduling
* Company coordination
* Placement drive management
* Reports & analytics

---

## 🚀 Live Demo

* Frontend (Netlify): 
* Backend (Render): 

---

## 🔑 Demo Login Credentials

You can use the following demo accounts to explore the system:

* Admin
  Email: [admin@gmail.com](mailto:admin@gmail.com)
  Password: 123456

* Company
  Email: [company@gmail.com](mailto:company@gmail.com)
  Password: 123456

* Student
  Create your own test account using the signup option.

---

## 👨‍💻 Roles & Features

### 🧑‍🎓 Student

* Submit applications with resume & cover letter (resumes stored securely in **Cloudinary**)
* Track application status
* Receive email notifications (via Nodemailer) for updates
* View & manage interview schedules
* Attend interviews via integrated **Jitsi Meet video conferencing**

### 🏢 Company

* Choose placement drive & post job openings
* Manage company profile
* View applications received (resumes fetched from Cloudinary)
* Update application status (triggers email to student)
* Schedule interviews and update results (emails sent to student)
* Conduct video interviews directly using **Jitsi integration**

### 👨‍💼 Admin

* Post & manage placement drives
* Manage student lists
* Create new placement drives
* View reports of past drives
* Export reports as PDF (using jsPDF / html-pdf)
* Visualize reports using Recharts

---

## ⚙️ Tech Stack

* Frontend: React.js, TailwindCSS, Redux (for state management)
* Backend: Node.js, Express.js
* Database: MongoDB
* Authentication: JWT
* File Storage: **Cloudinary** (for resumes and documents)
* Video Conferencing: **Jitsi Meet** (for online interviews)
* Email Notifications: Nodemailer
* State Management: Redux (used for managing authentication, roles, job postings, placement drives, interviews, and reports data consistently across the app)
* Charts & Reports: Recharts
* PDF Export: jsPDF / html-pdf
* Deployment:

  * Frontend → Netlify
  * Backend → Render

---

## 🗂️ Project Structure

```
/Placement-Management-System
 ├── backend   # Express.js API, MongoDB models & controllers
 ├── frontend  # React.js with TailwindCSS + Redux (slices, store, state management)
 └── README.md
```

