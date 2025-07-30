## 📝 To-Do List Web App Documentation
## 📌 Overview
This is a responsive and interactive To-Do List Web App built using HTML, CSS, and Vanilla JavaScript. It allows users to manage their daily tasks efficiently with features like task filtering, dark mode, and persistent storage using localStorage.

## 🧩 Features
#### ✅ Core Features
Add new tasks

Mark tasks as complete/incomplete

Delete tasks

Filter tasks by:

All

Active (incomplete)

Completed

Persistent storage using localStorage

#### 🌙 Bonus Features
Dark mode with toggle button

Theme preference saved across page reloads

Fully responsive design (mobile, tablet, desktop)

## 📁 File Structure
todo-app/
├── index.html       # Main HTML file
├── style.css        # Styling for the app
└── script.js        # Application logic
## 🔧 Technologies Used
Tech	Purpose
HTML5	Page structure
CSS3	Styling & responsiveness
JavaScript	Interactivity & data logic
localStorage	Save data in browser

## 📜 How It Works
#### 1. Adding a Task
User types a task in the input box and clicks "Add"

Task is added to the UI and saved to localStorage

#### 2. Mark as Complete/Incomplete
Click the task text to toggle its completion status

#### 3. Delete a Task
Click the "Delete" button to remove it from the list and storage

#### 4. Filter Tasks
Use filter buttons to switch between all, active, and completed views

#### 5. Dark Mode
Click the 🌓 button to toggle dark/light mode

Preference is saved using localStorage

## 🖥️ Responsive Design
Mobile-first approach

Uses Flexbox and media queries

Layout adapts for small screens:

Input/button stack vertically

Font sizes adjust accordingly

## 💾 Data Persistence
All tasks and theme settings are stored using:
localStorage.setItem('todos', JSON.stringify(todos));
localStorage.getItem('todos');
Tasks persist even after refreshing or closing the browser

Dark mode state is saved under the key theme

## 🔒 Limitations
No user accounts or server-side sync

No drag-and-drop reordering

Limited input validation (e.g., empty string is checked, but no advanced sanitization)

## 🚀 Future Improvements (Optional Ideas)
Add task due dates or priority levels

Use Firebase or Supabase for cloud storage

Add drag-and-drop sorting (e.g. with SortableJS)

Add animations or transitions

Offline-first Progressive Web App (PWA) with service workers

## 🧑‍💻 Author
Samarth Tripathi

GitHub: github.com/SamarthTripathi01

---

## ⚠️ Disclaimer

This project is created **solely for practice and learning purposes**.  
It is **not an original idea** nor intended for commercial use.  
Any resemblance to existing projects is purely coincidental.
