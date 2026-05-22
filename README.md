# CareerNest 🎯

**CareerNest** is a fully functional, feature-rich Job Portal mini-clone inspired by platforms like LinkedIn and Naukri. Built as part of the **SQ Rock Web Development Internship (Week 2, Task 1)**, this application simulates a dynamic, two-sided marketplace catering to both job seekers (**Candidates**) and recruiters (**Employers**).

The project focuses heavily on client-side state persistence, role-based access control, and dynamic DOM manipulation using pure vanilla web technologies.

🌐 **Live Demo:** [View CareerNest Live](https://sqrock-web-development-week2-carrer.vercel.app/)

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **State & Data Management:** `localStorage` (Simulating a persistent backend database)
- **Deployment:** Vercel

---

## 💡 Core Features

### 🔐 1. Authentication & Gateways

- **Role-Based Access Control (RBAC):** Users can register and log in as either a **Candidate** or an **Employer**.
- **Dynamic Dashboards:** The UI dynamically adapts based on the logged-in user's role.
- **Account Management:** Both roles have dedicated features to update profile information, change passwords, or permanently delete accounts.

---

### 👤 2. Candidate Portal

- **Job Discovery:** Browse, search, and filter through actively posted jobs.
- **Application System:** Apply for jobs via an integrated application form, including uploading/linking a resume.
- **Application Tracking:** Track application statuses in real-time (**Pending / Selected / Rejected**).
- **Job Management:** Save jobs for later or withdraw active job applications.

---

### 🏢 3. Employer Portal

- **Job Management (CRUD):** Post new job openings, edit existing job details, and delete inactive listings.
- **Applicant Pipeline:** View all candidates who applied for a specific job, review their profiles/resumes, and accept or reject their applications.

---

### 💾 4. Mock Backend (`localStorage` Architecture)

To keep data persistent across page reloads without a traditional backend database, `localStorage` is used to store:

- User registration credentials and session states.
- Active job posts, descriptions, and employer details.
- Submitted job applications mapped with live tracking statuses.

---

# 📂 Project Structure

The project follows a clean, lightweight, single-page application (SPA) architecture driven by conditional rendering:

```text
├── assets/
│   └── CarrerNest.png     # Project logos and image media assets
├── .gitignore             # Files to exclude from version control
├── index.html             # Main HTML entry point and page skeleton
├── README.md              # Project documentation (This file)
├── script.js              # JavaScript engine (Auth, Routing, CRUD operations)
└── style.css              # Custom responsive stylesheet (Modern UI/UX)
```

---

# 🚀 Local Installation & Setup

Follow these simple steps to run CareerNest locally on your machine.

## 📋 Prerequisites

You only need a modern web browser installed such as:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

(Alternatively, you can download the ZIP file of the source code.)

---

### 2️⃣ Navigate to the Project Folder

```bash
cd your-repo-name
```

---

### 3️⃣ Run the Project

#### ✅ Option A (Recommended)

Right-click `index.html` and select **Open with Live Server** (if using VS Code).

#### ✅ Option B

Simply double-click the `index.html` file to open it directly in any web browser.

---

# 📈 Acknowledgments

A special thanks to the team at **SQ Rock** for providing the structured guidance and foundational roadmap during my Web Development Internship.

---

# 🔗 Connect With Me

If you like this project, feel free to drop a ⭐ on the repository!

Happy Coding! 🚀

---

