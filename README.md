# 📚 Classroom Notifier

A full-stack web application that sends automated email notifications to students when they need to change classrooms between lectures. Never miss a classroom change again!

## 🎯 Problem Statement

In colleges, students often move between different classrooms every hour. It's easy to forget which room to go to next, especially during busy lecture schedules. This app solves that problem by automatically notifying students via email about upcoming classes and room changes.

## ✨ Features

- ✅ **User Authentication** – Register, login, and manage your profile
- ✅ **Timetable Management** – Add, edit, or delete classes for each day of the week
- ✅ **Email Notifications** – Automated reminders sent before each class (5/10/15 minutes)
- ✅ **Room Change Alerts** – Real-time notifications when your next class is in a different room
- ✅ **Dashboard Overview** – View today's schedule, next class countdown, and weekly timetable
- ✅ **Notification Settings** – Customize reminder timing and select active days
- ✅ **Account Deletion** – Permanently remove account with all associated data

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| **Frontend** | HTML5, CSS3, JavaScript (Vanilla) |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB (with Mongoose ODM) |
| **Email Service** | Nodemailer + Gmail SMTP |
| **Task Scheduling** | node-cron |
| **Authentication** | express-session, bcryptjs |
| **Deployment** | Render / Railway / Vercel |

## 📁 Project Structure
classroom-notifier/
├── public/ # Frontend files
│ ├── index.html # Login page
│ ├── register.html # Registration page
│ ├── dashboard.html # Dashboard
│ ├── timetable.html # Timetable management
│ └── settings.html # Notification settings
│
├── server.js # Main backend server
├── package.json # Dependencies
├── .env # Environment variables
└── README.md # Project documentation

text

## 🚀 Installation & Setup

### Prerequisites

- Node.js (v14 or higher)
- MongoDB (local or Atlas)
- Gmail account (for sending emails)
