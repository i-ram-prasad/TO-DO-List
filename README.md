# Simple To-Do List Application

This is a clean, simple, and responsive To-Do List application built with HTML, CSS, and vanilla JavaScript. It allows users to add, delete, and mark tasks as complete. The application leverages the browser's Local Storage to ensure that your tasks are saved even after you close the tab or refresh the page.

## Live Demo

You can view a live demo of the project hosted on GitHub Pages: **[Your Live Demo Link Here]**

## Features

* **Add Tasks:** Quickly add new tasks to your list using the input field.
* **Delete Tasks:** Remove tasks you no longer need with a dedicated delete button for each task.
* **Mark as Complete:** Simply click on a task to toggle its completed status.
* **Persistent Storage:** Your to-do list is saved in your browser's Local Storage, so you won't lose your progress between sessions.
* **Responsive Design:** A clean and modern dark-themed UI that looks great on all devices.

## Technologies Used

* **HTML5:** For the basic structure and content of the application.
* **CSS3:** For styling the application, including the layout, colors, and responsive design.
* **JavaScript (ES6):** For all the application logic, event handling, and interaction with Local Storage.

## File Breakdown

The project is structured into three main files:

* `index.html`: This file contains the basic HTML structure of the web page. It includes the main container, the title, the input field for new tasks, the "Add Task" button, and the unordered list (`<ul>`) where the tasks will be displayed.
* `style.css`: This file provides all the styling for the application. It defines the dark theme, the layout of the container, the appearance of buttons and input fields, and the styles for the to-do list items.
* `script.js`: This is the core of the application and handles all the dynamic functionality. Its responsibilities include:
    * Listening for the "Add Task" button click to create a new task.
    * Rendering tasks to the DOM.
    * Handling task deletion and completion toggles.
    * Saving the entire task list to the browser's `localStorage` and retrieving it when the page loads.

## How to Use

To run this project on your local machine:

1.  Download the `index.html`, `style.css`, and `script.js` files.
2.  Place them all in the same folder.
3.  Open the `index.html` file in your favorite web browser.
