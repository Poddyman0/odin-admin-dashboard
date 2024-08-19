Project Title: Todo List with Projects and Persistence

Project Overview:
This project is a dynamic todo list application that allows users to create and manage tasks across multiple projects. Users can add tasks with properties like title, description, due date, and priority, and can organize these tasks into different projects. The app provides a default project for basic task management but also allows users to create custom projects. It features the ability to view, edit, and delete todos. The app ensures data persistence using the Web Storage API (localStorage), so tasks and projects remain even after the page is refreshed.

Technologies and Skills Used:

JavaScript (ES6+): Used for creating and managing the application logic, as well as generating todos and projects dynamically.
HTML5/CSS3: For structuring and styling the user interface.
Webpack: Used for bundling the code and managing dependencies.
date-fns: A date utility library used for formatting and manipulating due dates.
LocalStorage (Web Storage API): To save and retrieve project and todo data, enabling persistence across sessions.
Modular Programming: Implemented a clear separation of concerns by organizing code into modules, separating application logic from DOM manipulation.
JSON Handling: Used to store and retrieve data in localStorage while ensuring proper serialization and deserialization of objects.
Features:

Project and Todo Management:

Users can create multiple projects to categorize their tasks.
A default project is provided to hold todos before custom projects are created.
Users can switch between projects and view all associated tasks.
Todo Item Properties:

Each todo item includes a title, description, due date, priority level, and optional notes.
Priority levels are visually indicated through colors, making it easy to differentiate between tasks.
Task Creation and Editing:

Users can create new todos by specifying properties like title, due date, and priority.
Todos can be edited to update their details or mark them as completed.
Dynamic User Interface:

Todos are displayed with their title and due date in a concise format. Higher-priority tasks are highlighted.
The interface allows users to expand a task to view or edit additional details, such as the full description.
Task Deletion:

Users can easily delete a task, removing it from the project.
Data Persistence:

The app automatically saves project and todo data to localStorage whenever a change is made (e.g., adding, updating, or deleting a todo).
On page load, the app checks localStorage and restores any saved projects and tasks, ensuring data is preserved across sessions.
Modular Code Structure:

The project is organized with a clear separation of concerns: application logic (e.g., creating and managing todos) is separated from DOM manipulation and rendering.
