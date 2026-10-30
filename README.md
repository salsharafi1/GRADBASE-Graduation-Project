# GRADBASE – Graduation Projects E-Library

A bilingual (Arabic / English) web platform that works as a central digital library for the graduation projects of the College of Computer Science and Information Systems (CSIS), Najran University.

> **Graduation project** · Bachelor of Information Systems · Najran University
> Team project (6 students) · Developed under academic supervision at Najran University

## 🎥 Demo

**[▶ Watch the demo video](demo.mp4)**

---

## 📌 The Problem

Students and faculty at CSIS had no organized place to browse previous graduation projects. This made it hard to:

- find and read past projects,
- understand what a graduation project is expected to include,
- check whether an idea had already been done,
- build on or improve existing work.

## 💡 The Solution

GRADBASE gathers all graduation projects in one searchable platform. Students and faculty submit projects, an admin reviews and approves them, and approved projects become available to the whole community.

## ✨ Key Features

| Area | What it does |
|---|---|
| **Browse & search** | Filter projects by department and year, and view the most popular and highest-rated work |
| **Bilingual interface** | Full Arabic and English support |
| **GradBot (AI assistant)** | Generates project ideas by academic domain, suggests research topics and tools, and clarifies project requirements in Arabic or English (logged-in users) |
| **Accessibility tools** | Text-to-audio, adjustable text size, dark and light mode |
| **Bookmarks, ratings & comments** | Save projects, rate them, and leave feedback (university members) |
| **Project submission & tracking** | Upload a project, then follow its status (Pending / Approved / Rejected, color-coded) in the Submission Tracker; approved files are automatically watermarked |
| **Admin approval workflow** | Admin reviews each request and approves or denies it; the project owner is notified |
| **Dashboard & reports** | Statistics such as departments, ratings, comments, visitors, and recently added projects |
| **Role-based access** | Four roles: Admin, Faculty Member, Student, Visitor |
| **Smart Report Guide** | A public, downloadable template showing the recommended chapters of a graduation report |

## 🧱 Tech Stack

- **Front-end:** HTML5, CSS3, JavaScript, Bootstrap
- **Back-end:** PHP, Python
- **Database:** MySQL
- **Other tools:** PDF.js (in-browser PDF viewing), draw.io (UML diagrams), LaTeX (documentation)

## 🔄 Methodology

The project followed **Agile**, working in sprints through six phases: Planning → Design → Development → Testing (unit, integration, system) → Deployment → Review.

## 📐 System Analysis & Design

### Use Case Diagram – Faculty Member
The faculty member can log in, search, upload files, view projects, bookmark, rate, use voice translation, chat with the bot, and switch language.

![Faculty use case diagram](project_useCase__1_.jpg)

### Sequence Diagram – Admin Approval
The admin logs in, views pending project requests, opens one, and either approves or denies it. The database is updated and the project owner is notified.

![Admin approval sequence diagram](seq_drawio.png)

## 👩‍💻 My Contribution

- Wrote the **project methodology** (Agile phases and how they were applied)
- Developed the **front-end interfaces** using HTML and CSS
- Contributed to the **system analysis**: use case and sequence diagrams

## 🚀 Future Work

Interactive learning modules, a discussion board, a recommendation system, a mobile app, cloud deployment, and expanding the library to all university faculties.

## 👥 Team

This was a team project of 6 students. My individual contribution is described above.

---
*Part of my portfolio: [github.com/salsharafi1](https://github.com/salsharafi1)*
