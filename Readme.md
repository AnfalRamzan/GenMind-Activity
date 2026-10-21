# 📚 StudyFlow – Smart Study Planner

Welcome to **StudyFlow**, a simple and colourful Smart Study Planner front page.
It is designed to help students organise their study life in one place: daily tasks, weekly timetable, study goals and exam reminders.

This project is built using only **HTML and CSS**, so it is easy to read, understand and modify, even for beginners.

---

## 📖 Project Overview

Students often find it hard to keep track of their tasks, classes, goals and upcoming exams. StudyFlow presents all of this information on a single, well-organised webpage.

**Purpose of the project:**

- To design a clean and attractive study planner layout
- To practise building a complete webpage using only HTML and CSS
- To show how modern design ideas like gradients, rounded cards and hover effects can be created without JavaScript or CSS frameworks

> **Note:** This is a front-end design project. The page shows sample data, and the "Add Task" form is visual only. It does not save or add tasks.

---

## ✨ Features

### 🧭 Header and Navigation
- Logo and website name (**StudyFlow**)
- Navigation links to Dashboard, Tasks, Timetable, Goals and Exams
- The header stays at the top of the page while scrolling (sticky header)

### 👋 Welcome Section
- A heading and short description of the planner
- Two buttons that jump to the Tasks and Timetable sections

### 📊 Dashboard Cards
- **Today's Tasks**: number of tasks for today
- **Completed Tasks**: tasks finished this week
- **Upcoming Deadlines**: number of deadlines coming soon
- **Study Progress**: percentage with a progress bar


### 💡 Daily Motivational Quote
- A study-related motivational quote shown on the dashboard, below the dashboard cards
- Displayed in a card that matches the existing theme, with gradients, rounded corners and a hover effect
- The quote is written in the HTML, so it can be changed by editing the quote text and author in `index.html`

### 📝 Task Management
- A form layout for adding a new task (task name, subject, due date and priority)
- A task list with checkboxes
- Ticking a checkbox crosses out the task (done with CSS only)
- Coloured priority tags: **High**, **Medium** and **Low**

### 🗓️ Weekly Timetable
- A Monday to Friday timetable with time slots
- Each subject has its own colour
- Rows are highlighted when you hover over them
- The table can scroll sideways on small screens

### 🎯 Study Goals
- Three goal cards, each with a progress bar and completion percentage

### ⏰ Exam Reminders
- Exam cards showing the date, subject, room, time and days left

### 🎨 Design and Interactivity
- Colourful gradients and rounded cards
- Hover effects on cards, buttons, links and task items
- Responsive layout that adjusts for mobile screens

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5**  | Structure and content of the page |
| **CSS3**   | Styling, colours, gradients, layout (Flexbox and Grid), hover effects and responsive design |

- ❌ No JavaScript
- ❌ No external CSS frameworks (like Bootstrap or Tailwind)

---

## 📁 Project Folder Structure

```
smart-study-planner/
│
├── index.html     # Main webpage (HTML structure + CSS inside a <style> tag)
└── README.md      # Project documentation (this file)
```

All the CSS is written inside the `<style>` tag in `index.html`, so the whole project works from a single file.

---

## 🚀 How to Run the Project Locally

You don't need to install anything. Just follow these steps:

1. **Download or clone** the project folder to your computer.

   If you are using Git:
```bash
   git clone <your-repository-link>
```

2. **Open the project folder.**

3. **Open `index.html`** in any web browser (Chrome, Firefox, Edge, etc.).
   - Double-click the file, **or**
   - Right-click it and choose **Open with → your browser**

4. *(Optional)* If you use **VS Code**, you can install the **Live Server** extension, right-click `index.html` and choose **"Open with Live Server"**. The page will refresh automatically every time you save a change.

That's it! 🎉

---

## 👥 Authors

This project was created as a group project by the following members:

| Member | Name | Role |
|--------|------|------|
| 1 | *[Member 1 Anfal]* | *[e.g. Project Manager]* |
| 2 |  Eman Ansar | Developer |
| 3 | *[Member 3 Name]* | *[e.g. Content and testing]* |

---

## ✏️ Member Contributions and Modifications

*Each member should write their own name and describe the changes they made to the project below.*

### Member 1: *[Name]*
- I have added a Daily Motivational quote. Displayed in a card that matches the existing theme, with gradients, rounded corners and a hover effect.

### How have i done it?
I gave a prompt to the claude and explained the feature that i wanted to add.
### prompt:  
Add a Daily Motivational Quote section to my existing Smart Study Planner in index.html. Requirements: Display a short study related motivational quote on the dashboard in a beautiful card that matches esisting theme. Do not change any existing features or rewrite the code. Only add the new section and the CSS needed for it. Tell me where i have to change or add the code. Tell me the exact line number where i have to change.



### Member 2: *[Name]*
- *[Describe the modification you made]*
- *[Describe another modification, if any]*

### Member 3: *[Name]*
- *[Describe the modification you made]*
- *[Describe another modification, if any]*

---

⭐ *Thank you for checking out StudyFlow – Plan Smarter, Study Better!*