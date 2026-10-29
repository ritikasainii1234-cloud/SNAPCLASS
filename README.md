# 🎓 SnapClass — AI-Powered Smart Attendance System

### Intelligent Attendance Management Using Face Recognition and Voice Identification

SnapClass is an AI-powered attendance management system designed to automate traditional classroom attendance using **Computer Vision, Voice Recognition, and Cloud Database Integration**.

The platform provides separate interfaces for teachers and students, enabling automated attendance tracking, subject management, and student enrollment.

## 🌐 Live Demo

**🌍 Official Website:** https://snapclass-landing-page-pink.vercel.app/

**🚀 AI Attendance Application:** https://snapclass-maiin-6pri6vnhnd2usdb9cvbph2.streamlit.app/

**🎨 Landing Page Repository:** https://github.com/ritikasainii1234-cloud/snapclass-Landing_Page

## ✨ Key Features

### 📸 1. AI-Powered Face Recognition
- Detects and recognizes student faces from uploaded classroom photographs.
- Supports attendance analysis across multiple images.
- Matches detected students against enrolled student records.
- Generates present/absent attendance results.

### 🎙️ 2. Voice-Based Attendance
- Provides an alternative voice attendance workflow.
- Supports sequential student identification through voice.
- Integrates voice attendance with subject-specific records.

### 👨‍🏫 3. Teacher Dashboard
- Teacher registration and login.
- Create and manage subjects.
- Share subject enrollment codes.
- Upload classroom images for face analysis.
- Review attendance results and historical records.

### 👩‍🎓 4. Student Interface
- Student-facing registration and enrollment workflows.
- Student identification for attendance.
- Integration with teacher-managed subjects.

### ☁️ 5. Cloud Database Integration
- Uses Supabase for storing and retrieving application data.
- Supports teacher, student, subject, and attendance records.
- Integrates attendance results with PostgreSQL-backed storage.

## 🛠️ Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| User Interface | Streamlit |
| Computer Vision | Face Recognition Pipeline, NumPy |
| Voice Processing | Voice Attendance Pipeline |
| Data Processing | Pandas, NumPy |
| Database | Supabase, PostgreSQL |
| AI Application Deployment | Streamlit Community Cloud |
| Landing Page | Flask, HTML, CSS, JavaScript |
| Landing Page Deployment | Vercel |
| Version Control | Git, GitHub |

## 🏗️ System Architecture

```text
                    SnapClass Landing Page
                           (Vercel)
                               |
                               v
                      Streamlit Application
                               |
                   +-----------+-----------+
                   |                       |
                   v                       v
             Teacher Portal          Student Portal
                   |                       |
                   v                       v
             Subject Management       Enrollment
                   |
           +-------+-------+
           |               |
           v               v
     Face Attendance   Voice Attendance
           |               |
           +-------+-------+
                   |
                   v
           Attendance Results
                   |
                   v
             Supabase Cloud
              (PostgreSQL)
                   |
                   v
           Attendance Records
```

## ⚙️ How SnapClass Works

**Step 1 — Registration**

Teachers and students access their respective interfaces.

**Step 2 — Subject Creation**

Teachers create subjects and share enrollment information with students.

**Step 3 — Student Enrollment**

Students enroll in the appropriate subjects.

**Step 4 — Attendance Capture**

Teachers choose between face-based and voice-based attendance.

**Step 5 — AI Processing**

The application processes attendance inputs and identifies students.

**Step 6 — Attendance Records**

Teachers review attendance results and save attendance records.

## 📸 Application Screenshots

Add screenshots of the following interfaces:

- Teacher Login
- Teacher Dashboard
- Subject Creation
- Face Recognition Attendance
- Voice Attendance
- Attendance Records
- Student Enrollment

Screenshots can be stored in a `screenshots/` directory.

Example:

```markdown
![Teacher Dashboard](screenshots/teacher_dashboard.png)
```

## 🚀 Running Locally

### 1. Clone the Repository

```bash
git clone https://github.com/ritikasainii1234-cloud/SNAPCLASS-01.git
```

### 2. Navigate to the Project

```bash
cd SNAPCLASS-01
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Environment

**Windows:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Configure Supabase

Configure the Supabase project URL and API credentials using the configuration mechanism expected by `src/database/config.py`.

Never commit credentials, passwords, or API secrets to GitHub.

### 7. Run the Application

```bash
streamlit run app.py
```

The application should open in your browser.

## 🎯 Project Objectives

- Reduce manual attendance management.
- Explore AI-based student identification.
- Provide multiple attendance methods.
- Simplify subject and student management.
- Maintain centralized attendance records.
- Deliver an accessible interface for teachers and students.

## 🔮 Future Improvements

- Attendance analytics and visualization.
- Improved recognition under challenging classroom conditions.
- Additional authentication and privacy safeguards.
- Exportable attendance reports.
- Performance optimization for larger classes.

## 👩‍💻 Project Information

**Project:** SnapClass — AI-Powered Smart Attendance System

**Domain:** Artificial Intelligence, Machine Learning, Computer Vision, Voice Recognition, and Web Development

**Application:** Classroom Attendance Management

---

⭐ If you find this project useful, consider starring the repository.