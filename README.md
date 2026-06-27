# 📝 To-Do List Application

## 📌 Project Overview

The To-Do List Application is a simple task management web application developed using HTML, CSS, and JavaScript. The purpose of this project is to help users manage their daily tasks efficiently. Users can add new tasks, edit existing tasks, delete tasks, and mark tasks as completed.

The application also uses Local Storage, which allows task data to remain available even after refreshing or closing the browser.

---

# 🚀 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Browser Local Storage

---

# 🎯 Project Objectives

The main objectives of this project are:

* Create a simple and user-friendly task manager.
* Allow users to add tasks.
* Allow users to edit tasks.
* Allow users to delete tasks.
* Allow users to mark tasks as completed.
* Store task data permanently using browser Local Storage.
* Improve understanding of DOM Manipulation and JavaScript CRUD Operations.

---

# ✨ Features

### 1. Add Task

Users can enter a task in the input field and click the Add Task button.

### 2. Edit Task

Users can modify an existing task without deleting it.

### 3. Delete Task

Users can remove unwanted tasks from the list.

### 4. Mark as Complete

Users can change the task status from Pending to Completed.

### 5. Local Storage

Tasks remain saved even after page refresh or browser restart.

### 6. Responsive User Interface

The application has a clean and simple design that works properly on different screen sizes.

---

# 🏗️ Project Structure

ToDo-List-App
│
├── index.html
--css
├── style.css
--Js
└── script.js
```

---

GitHub Profile:
https://github.com/dev-dhamandadiya/PR-1-HexSoftwares_To-Do-List-App.git

## Screenshot

![To Do List App](./Screenshot%202026-06-27%20203125.png)

# 📄 HTML Responsibilities

HTML is used to create:

* Project Heading
* Input Field
* Add Task Button
* Task Display Table
* Action Buttons

---

# 🎨 CSS Responsibilities

CSS is used to:

* Design the application layout
* Add colors and styling
* Create responsive UI
* Improve user experience
* Style buttons and tables

---

# ⚙️ JavaScript Responsibilities

JavaScript handles:

* Adding Tasks
* Editing Tasks
* Deleting Tasks
* Marking Tasks as Completed
* Displaying Tasks
* Managing Local Storage
* Updating the User Interface Dynamically

---

# 💾 Local Storage Implementation

The application uses browser Local Storage to save task data.

### Save Data

```javascript
localStorage.setItem("tasks", JSON.stringify(tasks));
```

### Retrieve Data

```javascript
JSON.parse(localStorage.getItem("tasks")) || [];
```

Benefits:

* Data remains after page refresh.
* No database required.
* Fast and simple implementation.

---

# 🔄 CRUD Operations

### Create

Add a new task.

### Read

Display all tasks.

### Update

Edit task details and update task status.

### Delete

Remove tasks from the list.

---

# 📚 JavaScript Methods Used

### map()

Used for updating task information.

### filter()

Used for deleting tasks.

### find()

Used for locating a specific task for editing.

### forEach()

Used for displaying tasks on the screen.

---

# 🎓 Learning Outcomes

Through this project, I learned:

* DOM Manipulation
* Event Handling
* JavaScript Functions
* Array Methods
* CRUD Operations
* Local Storage
* Dynamic UI Updates
* Frontend Development Fundamentals

---

# ✅ Conclusion

The To-Do List Application is a practical and beginner-friendly project that demonstrates core frontend development concepts. It provides users with an efficient way to manage tasks while helping developers understand HTML, CSS, JavaScript, CRUD Operations, and Local Storage implementation.

---

👩‍💻 Made By

Dhamanda Diya Hoshiyarsingh