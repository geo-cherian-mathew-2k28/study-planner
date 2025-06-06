# study-planner

Gplan.ai - Student Planner Web App
A lightweight, interactive web application designed to help students track, analyze, and schedule their study plans and academic tasks efficiently. This project aims to provide a professional, user-friendly interface to enhance productivity and organization for students.

Table of Contents
Features

Technologies Used

Getting Started

Usage

Mock Data

Future Enhancements

Contributing

License

Features
This planner site comes packed with essential features to support a student's academic journey:

Professional & Responsive Design: A clean, modern interface with a dark theme by default, featuring smooth transitions and rounded elements. It is designed to be visually appealing and user-friendly.

Theme Toggle: Easily switch between a dark and light theme to suit your preference. The chosen theme is saved for your next visit.

Motivational Quotes: The homepage features a dynamic motivational quote that changes with each theme toggle, offering a fresh dose of inspiration.

Academic Dashboard:

Overall Score: A prominent display of your simulated overall academic percentage.

Academic Suggestion: A quick tip or recommendation for study focus.

Today's Study Plan: A shortcut button to quickly navigate to your schedules.

Intuitive Sidebar Navigation: Quick access to all sections of the planner:

Home: The main dashboard.

Academic Calendar: A basic static calendar view to highlight important dates and deadlines.

Schedules & To-Do List: Manage your tasks, add new ones, mark them as complete, or delete them.

Reminders: Set personalized reminders with titles, descriptions, and specific date/times.

Subjects & Grades: View a list of your subjects along with mock grades and descriptions, with grades visually highlighted by color.

Study Timer: A built-in Pomodoro timer (25 minutes study, 5 minutes break) to help you focus and manage study sessions effectively.

Quick Schedules Button: A convenient button in the top right of the header for immediate access to your schedules.

Persistent Theme: Your theme choice is saved using browser's local storage.

Technologies Used
HTML5: For the core structure of the web application.

CSS3: Custom styles for unique design elements and transitions.

Tailwind CSS: A utility-first CSS framework for rapid UI development and responsive design.

JavaScript (ES6+): Powers all the interactive elements, dynamic content loading, data management (mock JSON), and functional features like the To-Do list, Reminders, and Study Timer.

Font Awesome: For a wide range of scalable vector icons used throughout the interface.

Getting Started
To get a local copy up and running, simply follow these steps.

Prerequisites
You only need a web browser to view this application.

Installation
Clone the repository (or download the HTML file):
If this were a full repository, you'd clone it:

git clone https://github.com/your-username/gplan-student-planner.git
cd gplan-student-planner

For this single-file setup, simply save the provided HTML code into a file named index.html (or any other .html extension).

Open in Browser:
Navigate to the saved index.html file in your file explorer and open it with your preferred web browser. That's it!

Usage
Navigation: Use the sidebar on the left to navigate between different sections of the planner.

Theme Toggle: Click the sun/moon icon in the top right corner to switch between dark and light themes.

Schedules: Go to the "Schedules" section to add, complete, or delete tasks from your To-Do list.

Reminders: Use the "Reminders" section to set new reminders with a title, description, and specific date/time.

Study Timer: In the "Study Timer" section, use the Start, Pause, and Reset buttons to manage your Pomodoro sessions.

Mock Data
The application currently uses in-memory mock data for subjects, grades, and to-do items. This means any changes you make (e.g., adding tasks, completing tasks, setting reminders) will not persist if you close or refresh the browser.

Future Enhancements
Data Persistence: Implement local storage or integrate with a backend (e.g., Firebase, local JSON server) to save user data permanently.

User Authentication: Add user login/registration functionality.

Dynamic Calendar: Integrate a more robust calendar library to allow adding and managing events directly on the calendar.

Notifications: Implement browser notifications for reminders and timer completion.

Customizable Pomodoro: Allow users to set custom study and break durations for the timer.

Detailed Analytics: Expand the "Overall Score" and "Academic Suggestion" to be based on real-time data input by the user, providing more granular insights into study habits and progress.

Drag-and-Drop: Enhance the To-Do list with drag-and-drop reordering.

Contributing
This project is a starting point for a student planner. Feel free to fork the repository and contribute to its development.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request
