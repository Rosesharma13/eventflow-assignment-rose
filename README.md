# eventflow-assignment-rose
A full-stack React + Node.js application for EventFlow, featuring event registration, organizer tools, scoring logic, and secure API endpoints.


# 🚀 Full Stack Developer Assignment – EventFlow

## 📌 Project Overview
EventFlow is a prototype event management platform built as part of a full stack developer assignment. It enables smooth interaction between attendees and organizers — including event creation, registration, and engagement tracking.

---

## 🎯 Features

### 👤 Attendee Dashboard
- Mock email-based registration/login
- View and register/unregister for events
- Real-time updates (optional feature)

### 🧑‍💼 Organizer Dashboard
- Login (mocked)
- Create, edit, delete event listings
- View attendee registrations
- Engagement score for each event

---

## 🔧 Tech Stack

- **Frontend**: React.js + Tailwind CSS
- **Backend**: Node.js + Express.js
- **Database**: MySQL
- **Authentication**: Mock email login
- **Deployment**: [Your deployment link here]

---

## 🔐 Security & Audit

- JWT-based mock auth middleware
- Passwords & sensitive data are encrypted
- Basic audit logging for all major actions (timestamp, user, event, action)

---

## 📊 Engagement Score

Each event has an automatically calculated engagement score based on:

- Registrations (0–2 pts)
- Attendance confirmation rate (0–2 pts)
- Organizer responsiveness (0–1 pt)
- Attendee feedback (0–1 pt)

(Mock/randomized data used)

---

## 🗃️ Database Schema

- `users` (attendee/organizer info)
- `events` (event details)
- `registrations` (attendee ↔ event mapping)
- `audit_logs` (action history)

---

## 🚀 Deployment

Deployed on: [e.g. Render / Vercel / AWS Free Tier]  
Frontend: [your-frontend-link]  
Backend: [your-backend-link]  

> Make sure to set environment variables correctly for database & backend URLs.

---

## 📄 Setup Instructions

1. Clone the repo:
```bash
git clone https://github.com/Rosesharma13/eventflow-assignment-rose.git
cd eventflow-assignment-rose


AUTHOR - Rose Sharma 
