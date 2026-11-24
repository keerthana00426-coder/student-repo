# student-repo
student name: keerthana, roll no:N26V01A0164,SEC -2
Deploy link:https://lighthearted-gaufre-f95c02.netlify.app/
# 🎓 CampusHub – Student Dashboard

## 📌 Project Overview

CampusHub is a responsive and interactive Student Dashboard Web Application designed to help students manage and monitor their academic activities in one place.

The dashboard provides students with easy access to their academic profile, attendance records, examination marks, class timetable, subjects, notifications, and college announcements.

It features a clean user interface, interactive components, and light/dark mode support to provide a convenient and user-friendly experience.

## ✨ Features

### 1. Dashboard
- Personalized welcome message.
- Displays student profile information.
- Shows overall attendance percentage.
- Displays upcoming class information with a live countdown timer.
- Shows recent unread notifications.
- Displays the latest college announcement.
- Provides a marks comparison chart.

### 2. Student Profile
- Student name and profile avatar.
- Roll number.
- Department and academic year.
- Email address and phone number.
- Faculty mentor information.
- CGPA and current semester GPA.

### 3. Attendance Management
- Displays overall attendance percentage.
- Shows subject-wise attendance records.
- Highlights subjects with attendance below 75%.
- Calculates the number of additional classes required to reach 75% attendance.
- Provides a monthly attendance calendar with present, absent, and holiday indicators.

### 4. Marks & Results
- Displays semester-wise examination results.
- Includes Internal 1, Internal 2, Assignment, and Final examination marks.
- Automatically calculates total marks.
- Assigns grades based on total marks.
- Provides a visual marks comparison chart.
- Allows students to switch between available semesters.

### 5. Timetable
- Displays the weekly class timetable.
- Organizes subjects according to days and time slots.
- Highlights the current day.
- Displays scheduled lunch breaks.
- Identifies the next upcoming class.
- Includes a live countdown timer for the next class.

### 6. Subject Management
- Displays enrolled subjects.
- Shows subject codes and credit values.
- Displays faculty names.
- Tracks syllabus completion percentage.
- Provides subject details through interactive buttons.
- Supports subject searching.

### 7. Notifications
- Displays academic notifications.
- Includes assignment deadlines, examination updates, fee reminders, and college events.
- Provides notification filtering by category.
- Allows individual notifications to be marked as read.
- Supports marking all notifications as read.
- Displays the unread notification count.

### 8. College Announcements
- Displays announcements from different college departments.
- Highlights pinned announcements.
- Shows announcement dates and publishing departments.
- Provides expandable announcement descriptions.
- Supports searching announcements.

### 9. Additional Features
- Light and dark theme toggle.
- Theme preference saved using browser local storage.
- Responsive layout for desktop and mobile devices.
- Interactive navigation between dashboard sections.
- Global search functionality.
- Accessible interface with keyboard focus indicators.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structure of the application |
| CSS3 | Styling, layouts, and responsive design |
| JavaScript | Application logic and interactivity |
| SVG | Attendance ring and marks visualization |
| Google Fonts (Inter) | Typography |
| Local Storage | Saving theme preferences |

## 📂 Project Structure

```text
CampusHub/
│
├── index.html
└── README.md
```

The application is developed using a single HTML file containing the HTML structure, CSS styling, and JavaScript functionality.

## 🚀 How to Run the Project

Follow these steps to run CampusHub on your computer.

**Step 1: Download or Clone the Repository**

```bash
git clone <your-repository-url>
```

**Step 2: Open the Project Folder**

```bash
cd CampusHub
```

**Step 3: Run the Application**

Open the `index.html` file in any modern web browser.

Alternatively, use the Live Server extension in Visual Studio Code.

No additional installation or build process is required.

## 📊 Sample Data

The application currently uses predefined sample student data.

The sample data includes:
- Student profile information.
- Six enrolled subjects.
- Subject-wise attendance records.
- Semester 3 and Semester 4 examination results.
- Weekly class timetable.
- Academic notifications.
- College announcements.

The sample student information can be modified in the `DATA` object inside the JavaScript section of `index.html`.

## ⚙️ Application Functionality

The application uses JavaScript to dynamically render different dashboard sections.

The main functionalities include:

- **Navigation:** Switches between different dashboard pages without reloading the browser.
- **Search:** Filters relevant subjects, notifications, and announcements.
- **Attendance Calculation:** Automatically calculates attendance percentages and required additional classes.
- **Grade Calculation:** Determines grades based on total examination marks.
- **Countdown Timer:** Calculates the time remaining until the next scheduled class.
- **Theme Management:** Switches between light and dark modes and saves the selected preference.
- **Notification Management:** Updates notification status and unread counts dynamically.

## 🔮 Future Enhancements

The project can be further improved by implementing:

- Backend integration using Node.js, Python, or Java.
- Database connectivity using MySQL or MongoDB.
- Student and faculty login authentication.
- Real-time attendance updates.
- Online assignment submission.
- Examination timetable downloads.
- Fee payment integration.
- Automatic notification updates.
- Faculty and administrator dashboards.
- Downloadable academic reports in PDF format.

## 🎯 Project Objective

The main objective of CampusHub is to simplify student academic management by providing a centralized platform where students can access important academic information, track their performance, monitor attendance, and stay updated with college activities.

## 👩‍💻 Project Information

**Project Name:** CampusHub – Student Dashboard

**Project Type:** Web Development Project

**Frontend:** HTML, CSS, JavaScript

**Application:** Student Academic Management Dashboard

**Current Version:** 1.0

---

⭐ **CampusHub – Everything a student needs, all in one place!**
