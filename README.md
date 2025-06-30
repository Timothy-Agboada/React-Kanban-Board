## 🚀 30-Day Coding Challenge: Day 20

This project is the twentieth entry in my 30-day coding challenge. Today's goal was to build a highly interactive and complex UI component: a Kanban-style task board. This project focuses on advanced state management, the native HTML Drag and Drop API, and creating a polished, developer-focused user interface.

### 📖 Project Overview

This is a fully functional, Trello-like Kanban board application built with React. It allows users to manage tasks across three columns: "To Do," "In Progress," and "Done." Users can seamlessly add new tasks to the "To Do" column and drag and drop tasks between any of the columns to update their status. The application features a professional dark theme and provides a clear, at-a-glance view of the project's state with task counters in each column.

### ✨ Live Demo & Screenshot

Below is a screenshot of the application's interface.
![Jun-30-2025 15-30-53](https://github.com/user-attachments/assets/da102a8f-f62e-4c6d-b139-d024efcee2d5)


### 🌟 Key Features

* **Drag & Drop Functionality:** Implements the native HTML Drag and Drop API to allow for smooth and intuitive reordering of tasks between columns.
* **Add New Tasks:** A dedicated form allows users to easily add new tasks to the "To Do" column.
* **Complex State Management:** Manages a normalized state structure (an object containing tasks, columns, and column order) which is a scalable pattern for complex applications.
* **Immutable State Updates:** Adheres to React best practices by treating state as immutable, creating new state objects for every update to ensure predictable rendering.
* **Task Counters:** Each column header displays a live count of the tasks it contains.
* **Professional Dark Theme:** A sleek, developer-focused dark mode UI styled with Tailwind CSS.
* **Component-Based Architecture:** The application is broken down into logical, reusable components (`Column`, `Task`, `AddTaskForm`).

### 💻 Technologies Used

This project was built using a modern, lightweight React setup.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3e.svg?style=for-the-badge&logo=babel&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

* **React:** The core library for building the user interface.
* **ReactDOM:** Used to render the React component into the browser's DOM.
* **Babel:** Used as a transpiler to convert JSX into standard JavaScript.
* **Tailwind CSS:** For all styling and layout.
* **Font Awesome:** For icons.

### 🛠️ How to Run Locally

This project is set up to be extremely simple to run, with no build process required:

1.  **Clone the repository (or download the code):**
    ```bash
    git clone https://github.com/timothy-agboada/react-kanban-board.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd react-kanban-board
    ```
3.  **Open the `index.html` file in your web browser.** The CDN links will handle loading all necessary libraries automatically.

### 🎯 Learning Objectives

This project was a deep dive into several advanced front-end concepts:

* **HTML Drag and Drop API in React:** Learning how to use the native browser API for drag events (`onDragStart`, `onDragOver`, `onDrop`) within a React component structure.
* **Managing Complex, Nested State:** Gaining experience with a more realistic, normalized state structure and writing functions to update it immutably.
* **Handling User-Generated Data:** Implementing the full flow of adding new data to the application state based on user input.
* **Component Communication:** Passing data and callback functions (`onDropTask`, `onAddTask`) through multiple layers of components to manage state from a central location.
