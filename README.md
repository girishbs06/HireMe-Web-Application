Project Overview
HireMe is a modern job recruitment web application designed to bridge the gap between students looking for internships or job opportunities and recruiters seeking talented candidates. Built using the Flask framework, it offers separate modules for students and recruiters, streamlining the job application process through a clean, responsive interface and user-friendly features.
Web Pages & Features
👤 User Roles
Students – Can register, log in, browse and apply for jobs.
Recruiters – Can post job listings, view applicants, send acceptance/rejection emails, contact students directly, and generate reports.
🧱 Main Pages
index.html – Homepage with platform intro
student_register.html – Student registration form
recruiter_register.html – Recruiter registration form
student_login.html – Student login portal
recruiter_login.html – Recruiter login portal
student_home.html – Student dashboard to view & apply to jobs
recruiter_home.html – Recruiter dashboard to manage job postings
create_job.html – Page for recruiters to post new jobs
job_details.html – Job description view for students
recruiter_job_details.html – Recruiter view with job applicants
student_reset_password.html – Password recovery for students
recruiter_forgot_password.html – Password recovery for recruiters
report.html – Dashboard summary for recruiters
📊 Database Schema
students: Stores student user data
recruiters: Stores recruiter user data
jobs: Stores job details
student_applications: Tracks applications submitted by students
🧩 Key Functionalities
✅ Secure Registration/Login – Separate login systems for students and recruiters
📄 Job Posting & Management – Recruiters can post jobs, edit, delete, and view applicants
📌 Job Listings & Applications – Students can browse available jobs and apply instantly
🔐 Password Recovery System – Email-based password reset for both roles
📧 Application Response via Email – Recruiters can send customized acceptance or rejection emails
📞 Direct Contact Feature – Recruiters can reach out to students for further communication
📊 Application Reports – Recruiters can view statistics on applications and postings
🚫 Job Status Control – Closed jobs are hidden from students and cannot be applied to
