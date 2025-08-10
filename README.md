Online Examination System

Overview

The Online Examination System is a Django-based web application designed to facilitate secure and efficient online exams. It supports multiple-choice question (MCQ) exams with features like auto-submission, focus monitoring, and instant score calculation. The system provides separate interfaces for students, professors, and administrators.

Features





Auto-Submit: Exams submit automatically when the timer expires.



Focus Monitoring: Alerts professors via email if a student switches tabs/windows 5 times.



Automatic Scoring: Calculates and displays scores instantly after submission.



User Roles:





Students: Take exams and view results.



Professors: Create/manage exams and monitor students.



Admins: Manage users and assign professor roles.



Email Notifications: Sends alerts for suspicious activity.



Secure: Professors require admin verification.

Technologies





Backend: Python, Django



Frontend: HTML, CSS, JavaScript



Database: SQLite (default, configurable for others)



Dependencies: Managed via Pipenv (Django, argon2-cffi)



Email: SMTP-based (e.g., Gmail)