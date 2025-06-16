# 🐞 Bug/Task Tracker Web App

A full-featured bug and task tracking web application built using **Next.js**. The app is designed to streamline task management and bug tracking workflows with user roles, authentication, time tracking, and clean dashboards.

---

## 🚀 Demo

🔗 Live Demo: [Visit the deployed app](https://glittery-croquembouche-ba7270.netlify.app/)

🎥 Video Walkthrough: [Watch on YouTube](https://drive.google.com/file/d/18taQRUY6-itCXFzYKqHC1i_dLLu6Ksdy/view?usp=drivesdk)

---

## 🔐 Authentication & Roles

- 🔑 Simple login system with mock authentication (hardcoded users).
- 👤 Roles:
  - **Developer:** Create, edit, close tasks and bugs.
  - **Manager:** View all tasks, approve/reject bug closures.

---

## 🖥️ Features

### ✅ Dashboard
- Developer-specific dashboard showing assigned tasks/bugs.
- Manager dashboard for viewing all open/closed/pending bugs.
- 📈 Visual trend line for daily concurrent tasks.

### 📝 Task & Bug Management
- Create tasks/bugs with fields like:
  - Title, Description, Priority, Status, Assignee, Dates, etc.
- Filter/sort by Priority, Status, etc.
- Developer can request bug closure.
- Manager can approve/reject bug closure.

### ⏱️ Time Tracker
- Log time against each task.
- View total hours spent.
- Managers can view time logs of all developers.

---

## 🎨 UI/UX

- Fully responsive design.
- Clean, intuitive layout with a mobile-first approach.
- Built with modern CSS and reusable components.

---

## 🛠️ Tech Stack

| Tech        | Description                    |
|-------------|--------------------------------|
| Next.js     | React framework (frontend)     |
| React       | UI library                     |
| Zustand     | Lightweight state management   |
| Styled-components | CSS-in-JS styling       |

---

## 📁 Installation & Setup

```bash
# Clone the repository
git clone https://github.com/your-username/bug-task-tracker.git

# Navigate to the project directory
cd bug-task-tracker

# Install dependencies
npm install

# Run the development server
npm run dev
