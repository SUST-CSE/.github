# 🎓 SUST-CSE Departmental Portal

### **Lead Architect & Full-Stack Developer:** [Zubayer Hossain Uday](https://github.com/uday-zubayer)

> **A professional, unified digital ecosystem built for the Department of Computer Science and Engineering, SUST.**

Welcome! This portal is a comprehensive solution designed to bridge the gap between academic management, student society activities, and departmental transparency. As the lead developer, I built this to replace fragmented systems with a modern, scalable, and modular architecture.

---

## 📖 Project Vision

In a fast-paced academic environment like CSE SUST, information often gets lost in emails and social media groups. This project was conceived to:

1. **Centralize Resources:** A single hub for students, faculty, and alumni.
2. **Ensure Transparency:** A dedicated module for public financial auditing of society funds.
3. **Empower Societies:** Hierarchical task management for departmental clubs.

---

## �️ Technical Architecture

To demonstrate professional-grade engineering, the project is hosted under a GitHub Organization and follows a **Modular Monolith** pattern:

* **Frontend Core:** A high-performance SPA built with **Next.js 16** (App Router) and **Material UI**.
* **Backend API:** A type-safe, RESTful service built with **Node.js, TypeScript,** and **Express**.
* **Database:** A flexible document-based schema using **MongoDB** and **Mongoose**.

---

## 🌟 High-Impact Features

### � Multi-Tier Governance (RBAC)
Customized dashboards for **Students, Teachers, and Admins**, ensuring that the right people have the right tools.

### 💰 Financial Transparency Module
A unique system allowing society leaders to post income/expenses with image/PDF proof, viewable by the entire department to ensure accountability.

### 📝 Academic & Community Hub
* **Blogging Engine:** Full Markdown support for technical articles.
* **Notice Board:** Real-time event and academic announcements.
* **Directories:** Organized, searchable databases for Faculty and Alumni.

---

## 🛠️ User Journey & System Governance

### 1. User Verification & Onboarding
- **Registration**: All users (Students, Teachers, Alumni) register via a unified portal.
- **Admin Approval**: To maintain data integrity, every registration must be reviewed and approved by an administrator before access is granted.
- **Granular Permissions**: Admins can assign specific rights (e.g., `MANAGE_BLOGS`, `MANAGE_ACCOUNTS`, `MANAGE_SOCIETIES`) to trusted students or faculty, delegating departmental responsibilities.

### 2. Member Management
- **Student Profiles**: Dynamic profiles displaying registration details, society involvement, and personal blog posts.
- **Teacher Directory**: A formal directory for faculty members to share resources and departmental contact info.
- **Alumni Network**: A dedicated section to keep former students connected with the department's latest achievements.

### 3. Society & Work Flow
- **Work Assignment Hierarchy**: Society leaders (e.g., President, Secretary) can assign tasks to members. The system enforces a **numerical hierarchy** (Rank 1 to 5), ensuring only higher-ranking members can assign work to subordinates.
- **Task Tracking**: Members receive live notifications of assigned work and can track their status directly from their dashboard.

### 4. Financial Auditing
- **Public Ledger**: Any student or faculty member can view the department's financial status.
- **Evidence-Based Reporting**: Every transaction (Income or Expense) requires a title, category, and an optional **proof file (Image or PDF)**, making fraud virtually impossible.
- **Delegated Accounting**: Specific students can be granted `MANAGE_ACCOUNTS` rights to record transactions on behalf of a society.

---

## 🛠️ Tech Stack & Tools

| Layer | Technologies |
| --- | --- |
| **Frontend** | Next.js 16, Redux Toolkit, GSAP, Tailwind CSS, Lucide |
| **Backend** | TypeScript, Node.js, Express, Zod, JWT |
| **Database** | MongoDB, Cloudinary (Storage) |
| **DevOps** | Git (Org Workflow), Nodemailer, Helmet, Express-Rate-Limit |

---

## 🚀 Quick Start

<details>
<summary><b>View Installation Instructions</b></summary>

### 1. Backend Setup
```bash
cd Backend && npm install
cp .env.example .env
# Set your MONGO_URI, JWT_SECRET, and CLOUDINARY credentials in .env
npm run seed:admin
npm run dev
```

### 2. Frontend Setup
```bash
cd Frontend && npm install
# Set NEXT_PUBLIC_API_URL in .env
npm run dev
```
</details>

---

## � License & Contact

This project is licensed under the ISC License.

**Maintained by:** [Zubayer Hossain Uday](mailto:uday.sust.cse@gmail.com)

*Feel free to reach out for collaboration or deployment queries.*
# .github
