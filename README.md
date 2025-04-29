<h1 align="center">🧠 ITME Journal Publication Website</h1>

<p align="center">
  <b>Innovations and Trends in Multidisciplinary Engineering</b><br/>
  <i>Research Paper Submission & Review System</i>
</p>

<p align="center">
  <img src="./banner.jpg" alt="ITME Banner" width="80%" />
</p>

---

## 👥 Team Members

<table>
  <tr>
    <td><b>Piyush Kumar Sharma</b></td>
    <td>B.Tech CSE (AI & ML)</td>
    <td>Roll No: 2401730173</td>
  </tr>
  <tr>
    <td><b>Yashraj Pahuja</b></td>
    <td>B.Tech CSE (AI & ML)</td>
    <td>Roll No: 2401730205</td>
  </tr>
</table>

---

## 📌 Project Overview

The **ITME Journal Publication Website** is a full-stack research submission system built using the MERN stack.  
It enables authors to upload their research papers in PDF format, track their status, and receive email updates.  
Admins can manage submissions, review papers, and send decisions to authors automatically.

> Originally branded as **PEI – Pioneering Engineering Insight**, now rebranded to **ITME**.

---

## ✨ Key Features

- Upload and preview research papers (PDF.js)
- OTP-based user registration and login
- Admin panel for status updates and paper reviews
- Email notifications using Nodemailer
- Responsive frontend for authors & admins
- Real-time status updates

---

## 🛠️ Tech Stack

| Layer       | Tools Used                             |
|------------|------------------------------------------|
| Frontend   | React.js, Tailwind CSS                   |
| Backend    | Node.js, Express.js                      |
| Database   | MongoDB Atlas / VPS-hosted MongoDB       |
| Auth       | JWT, OTP verification                    |
| PDF Viewer | PDF.js (v4.7.76)                         |
| Email      | Nodemailer (SMTP)                        |
| File Store | Server-side (`/uploads/`)                |

---

## 🗂️ File Structure

```bash
Piyush_Sharma_CSEAIMLB_ITME1/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── uploads/             # PDF files
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
├── .env
├── README.md
└── package.json