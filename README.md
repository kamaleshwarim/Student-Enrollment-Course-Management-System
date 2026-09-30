# Students Environment and Course Management System

A college mini-project to manage **students, courses, enrollments, attendance** and the **learning environment** (classrooms, labs, library) including student feedback on facilities.

## Features
- Student, course and enrollment management (add / view / delete)
- Room and facility tracking (capacity, projector, Wi-Fi)
- Student feedback ratings for the learning environment
- Dashboard summary (totals, average room rating)

## Tech Stack
HTML, CSS, JavaScript (demo front-end) · MySQL (`database/schema.sql`)

## Database
7 tables: `departments, students, instructors, rooms, courses, enrollments, attendance, env_feedback`.
Run: `mysql -u root -p < database/schema.sql`

## Project Structure
```
├── index.html          # page structure
├── style.css           # styling
├── script.js           # add / delete logic
├── Project_PPT.pptx    # presentation
├── README.md
└── database/
    └── schema.sql      # MySQL tables, sample data, queries
```

## Run the demo
Open `index.html` in a browser.

## Team
1. Thirukalai T
2. Anusuya A
3. Kamaleshwari M
4. Rajeswari K
5. Sivabharathi K

**Guide:** Dr. T. Sundaravadivel, Assistant Professor

## Upload to GitHub
```bash
git init
git add .
git commit -m "Initial commit: Students Environment and Course Management"
git branch -M main
git remote add origin https://github.com/<your-username>/student-env-course-mgmt.git
git push -u origin main
```
