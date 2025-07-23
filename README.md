School Portal & Attendance Management App
A comprehensive, single-page web application designed to streamline school management for three key user roles: Administrators, Teachers, and Students. This interactive prototype is built with vanilla JavaScript, HTML, and Tailwind CSS, and it simulates a complete school environment with a rich, static dataset.

Live Demo
https://harshal174.github.io/Attendace-App/
(Note: Replace the above URL with your actual GitHub Pages link after deployment.)

Features
The application is a role-based system with distinct dashboards and functionalities for each user type.

👨‍💼 Admin Portal
The Admin has full oversight and management capabilities over the entire school's data.

Dashboard: An at-a-glance view of key metrics like total teachers and pending leave requests.

Manage Teachers:

View a searchable list of all teachers.

Add new teachers with their qualifications and details.

Activate or deactivate teacher accounts.

Click on a teacher's name to view their detailed profile and edit their information.

Manage Classes:

View all classes and their assigned Class Teachers.

Create new classes and assign an available teacher.

Drill down into a class to see a searchable list of all enrolled students.

Add new students to a class.

Manage Schedule:

View a master timetable for all classes and all periods.

Click on any period to assign or change the subject teacher from a list of available staff.

Manage Announcements:

Create, edit, and delete school-wide announcements that are visible to students.

Reports:

Student Attendance Report: View a detailed, color-coded monthly attendance grid for any class. Includes month/year navigation and an "Export to CSV" feature.

Student Assessment Report: View a list of students in any class, and click on a student to see their complete academic summary, including subject-wise marks and overall percentage.

Teacher Attendance Report: View a detailed monthly attendance grid for all teachers.

👩‍🏫 Teacher Portal
The Teacher portal is focused on daily classroom management and their personal schedule.

Dashboard: A personalized dashboard showing the teacher's schedule for the day.

Mark Attendance: Teachers can click on any period in their schedule to be taken directly to the attendance marking page for that specific class.

Self-Attendance: Teachers can mark themselves as "Present" or "On Leave" for the day.

Attendance History: A full calendar view where teachers can review the attendance they submitted on any past date.

Enter Marks: An intuitive workflow to select a class, subject, and exam to enter and save marks for students.

Apply for Leave: A simple form to apply for leave, which is then sent to the admin for approval.

Profile View: Teachers can view their own detailed profile, including their unique Teacher ID, qualifications, and profile picture.

🎓 Student Portal
The Student portal provides students with direct access to their academic and personal information.

Dashboard: A personalized dashboard showing the student's class, their attendance status for the day, and their daily schedule.

My Schedule: An interactive view of their daily class schedule, with clickable teacher names.

Teacher Profiles: By clicking a teacher's name on the schedule, students can view that teacher's detailed profile, including their qualifications and photo.

Report Card: A detailed view of their marks for all exams, broken down by subject, with total marks and percentages calculated.

Attendance History: A complete, read-only list of their own attendance records.

Announcements: A feed of the latest school-wide announcements posted by the admin.

Getting Started
This project is a single HTML file with no external dependencies beyond the CDN links for Tailwind CSS and Chart.js.

Download the Code:

Clone the repository or download the index.html file.

Open the File:

Open the index.html file in any modern web browser (like Chrome, Firefox, or Edge).

The application will run locally in your browser.

Test Credentials
You can use the following credentials to test the different user roles:

Admin:

Login ID: admin@school.com

Password: password

Teacher:

Login ID: teacher@school.com

Password: password

Student:

Student ID: (Find a valid 10-digit ID from the "Manage Classes" -> Student List in the Admin panel)

Password (DOB): (Find the corresponding DOB in YYYY-MM-DD format from the student's details)

A pre-configured test student's credentials will also be displayed on the login page when the "Student" role is selected.

Technology Stack
Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Charts: Chart.js (via CDN)

Deployment
This static site is deployed using GitHub Pages. Any push to the main branch will automatically trigger a new deployment.
