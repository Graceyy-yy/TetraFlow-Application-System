# TetraFlow-Application-System
# Overview
This repository contains the code for the TetraFlow Application System, designed to handle the application process for a specific course or program. The system allows users to apply through a web form, and administrators can monitor applications through a dashboard. The backend handles the logic of checking applicants' eligibility and available space in the program and sends automated emails based on the outcome.
# Collaborators
This project is a collaborative effort by the following team members:
1. Tariro Grace Kangausaru
2. Unthatile Michel Mahlangu
3. Mosa Penya
4. Rubina Moyakhe

# Features
# Frontend (User Interface)
1. Application Form: A user-friendly form where applicants can input their details such as name, email, grades, etc.
2. Admin Dashboard: A dashboard for administrators to monitor and manage applications, view applicant information, and track the status of each submission.
   
# Backend (Logic & Processing)
1. Database: A database stores applicant information securely.
2. Admission Logic: Verifies if the applicant meets the admission criteria based on grades.
Checks the availability of space in the course/program.
Sends automated emails to applicants with their acceptance or rejection status.

# Tech Stack
# Frontend:
React.js, Vue.js, or basic HTML/CSS with JavaScript (you can choose the appropriate one for your project).

# Backend:
Node.js with Express, Django, or Laravel.
Database: MySQL, PostgreSQL, or Firebase.
Email Service: Nodemailer (Node.js), SMTP, or Mailgun (for sending emails).

# Process Flow
1. User Application: The user submits their details through the web form.
2. Eligibility Check: The system checks if the applicant’s marks meet the admission criteria.
3. Space Availability Check: The system verifies if there is available space in the program/course.

# Decision:
1. Accepted: If the applicant is eligible and space is available, they receive an acceptance email.
2. Rejected: If the applicant does not meet the criteria or space is unavailable, they receive a rejection email.
3. Admin Dashboard: The admin can view and manage applications, track their status, and take further actions.
