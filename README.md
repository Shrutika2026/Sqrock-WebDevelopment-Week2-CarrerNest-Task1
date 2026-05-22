# CareerNest 🎯

**CareerNest** is a fully functional, feature-rich Job Portal mini-clone inspired by platforms like LinkedIn and Naukri. Built as part of the **SQ Rock Web Development Internship (Week 2, Task 1)**, this application simulates a dynamic, two-sided marketplace catering to both job seekers (**Candidates**) and recruiters (**Employers**).

The project focuses heavily on client-side state persistence, role-based access control, and dynamic DOM manipulation using pure vanilla web technologies.

🌐 **Live Demo:** [CareerNest](https://sqrock-web-development-week2-carrer.vercel.app/)

---

# 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **State & Data Management:** `localStorage` (Simulating a persistent backend database)
- **Deployment:** Vercel

---

# 💡 Core Features

## 🔐 1. Authentication & Gateways

- **Role-Based Access Control (RBAC):** Users can register and log in as either a **Candidate** or an **Employer**.
- **Dynamic Dashboards:** The UI dynamically adapts based on the logged-in user's role.
- **Account Management:** Both roles have dedicated features to update profile information, change passwords, or permanently delete accounts.

---

## 👤 2. Candidate Portal

- **Job Discovery:** Browse, search, and filter through actively posted jobs.
- **Application System:** Apply for jobs via an integrated application form, including uploading/linking a resume.
- **Application Tracking:** Track application statuses in real-time (**Pending / Selected / Rejected**).
- **Job Management:** Save jobs for later or withdraw active job applications.

---

## 🏢 3. Employer Portal

- **Job Management (CRUD):** Post new job openings, edit existing job details, and delete inactive listings.
- **Applicant Pipeline:** View all candidates who applied for a specific job, review their profiles/resumes, and accept or reject their applications.

---

## 💾 4. Mock Backend (`localStorage` Architecture)

To keep data persistent across page reloads without a traditional backend database, `localStorage` is used to store:

- User registration credentials and session states.
- Active job posts, descriptions, and employer details.
- Submitted job applications mapped with live tracking statuses.

---

# 📂 Project Structure

```text
├── assets/
│   └── CarrerNest.png
├── .gitignore
├── index.html
├── README.md
├── script.js
└── style.css
```

---

# 🚀 Local Setup & Development Guide

Follow these steps to download the repository, run it on your own PC, and make your own changes to the code.

---

# 📋 Prerequisites

You only need:

- A modern web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari)
- A code editor (Recommended: Visual Studio Code)
- Git installed on your system (Optional but recommended)

---

# 🛠️ 1. Download the Project from GitHub

## ✅ Option A: Using Git (Recommended)

Open **Command Prompt**, **Terminal**, or **Git Bash** and run:

```bash
# Clone the repository
git clone https://github.com/Shrutika2026/Sqrock-WebDevelopment-Week2-CarrerNest_AdminAnalyticsPortal-Task2.git

# Open the project folder
cd Sqrock-WebDevelopment-Week2-CarrerNest_AdminAnalyticsPortal-Task2
```

---

## ✅ Option B: Download ZIP File

1. Open your GitHub repository.
2. Click the green **Code** button.
3. Select **Download ZIP**.
4. Extract the ZIP file anywhere on your computer.

---

# 💻 2. Open the Project in VS Code

1. Open **Visual Studio Code**
2. Click:

```text
File → Open Folder
```

3. Select the project folder.

---

# ✏️ 3. Edit the Project Files

You can modify:

| File | Purpose |
|------|----------|
| `index.html` | Structure and layout |
| `style.css` | Styling, colors, responsiveness |
| `script.js` | Logic, authentication, CRUD operations |
| `assets/` | Images and media files |

---

# ▶️ 4. Run the Project Locally

## ✅ Method 1: Using VS Code Live Server (Recommended)

### Install Live Server Extension

1. Open VS Code
2. Go to Extensions
3. Search:

```text
Live Server
```

4. Install the extension by **Ritwick Dey**

---

### Start the Project

1. Open `index.html`
2. Right-click inside the file
3. Click:

```text
Open with Live Server
```

OR

Click the **Go Live** button in the bottom-right corner of VS Code.

---

### Local URL Example

The project will open automatically in your browser:

```text
http://127.0.0.1:5500/index.html
```

---

## ✅ Method 2: Run Directly in Browser

1. Open the project folder
2. Double-click `index.html`

The project will open in your browser using a `file://` path.

---

# 🔄 5. Save Changes & Push Updates to GitHub

After making changes:

```bash
# Check changed files
git status

# Add files
git add .

# Commit changes
git commit -m "Updated CareerNest project"

# Push to GitHub
git push origin main
```

---

# 🌐 Deployment

This project is deployed using **Vercel**.

Live Link:

[CareerNest](https://sqrock-web-development-week2-carrer.vercel.app/)

---

# 📈 Acknowledgments

Special thanks to **SQ Rock** for providing the internship opportunity, project guidance, and learning roadmap during the Web Development Internship Program.

---

# 🔗 Connect With Me

If you like this project, feel free to ⭐ star the repository and connect with me on LinkedIn.

Happy Coding 🚀

---

# ⚠️ Important Note

Your image file is currently named:

```text
CarrerNest.png
```

(With double `r`)

If you later rename it to:

```text
CareerNest.png
```

make sure to update the filename everywhere in your project to avoid broken image paths.
