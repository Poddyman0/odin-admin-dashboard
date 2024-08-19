<strong>Project Title:</strong> Todo List with Projects and Persistence

<strong>Project Overview:</strong>
This project is a dynamic todo list application that allows users to create and manage tasks across multiple projects. Users can add tasks with properties like title, description, due date, and priority, and can organize these tasks into different projects. The app provides a default project for basic task management but also allows users to create custom projects. It features the ability to view, edit, and delete todos. The app ensures data persistence using the Web Storage API (localStorage), so tasks and projects remain even after the page is refreshed.

<strong>Technologies and Skills Used:</strong>

<ul>
  <li><strong>JavaScript (ES6+):</strong> Used for creating and managing the application logic, as well as generating todos and projects dynamically.</li>
  <li><strong>HTML5/CSS3:</strong> For structuring and styling the user interface.</li>
  <li><strong>Webpack:</strong> Used for bundling the code and managing dependencies.</li>
  <li><strong>date-fns:</strong> A date utility library used for formatting and manipulating due dates.</li>
  <li><strong>LocalStorage (Web Storage API):</strong> To save and retrieve project and todo data, enabling persistence across sessions.</li>
  <li><strong>Modular Programming:</strong> Implemented a clear separation of concerns by organizing code into modules, separating application logic from DOM manipulation.</li>
  <li><strong>JSON Handling:</strong> Used to store and retrieve data in localStorage while ensuring proper serialization and deserialization of objects.</li>
</ul>

<strong>Features:</strong>

<ul>
  <li><strong>Project and Todo Management:</strong>
    <ul>
      <li>Users can create multiple projects to categorize their tasks.</li>
      <li>A default project is provided to hold todos before custom projects are created.</li>
      <li>Users can switch between projects and view all associated tasks.</li>
    </ul>
  </li>
  <li><strong>Todo Item Properties:</strong>
    <ul>
      <li>Each todo item includes a title, description, due date, priority level, and optional notes.</li>
      <li>Priority levels are visually indicated through colors, making it easy to differentiate between tasks.</li>
    </ul>
  </li>
  <li><strong>Task Creation and Editing:</strong>
    <ul>
      <li>Users can create new todos by specifying properties like title, due date, and priority.</li>
      <li>Todos can be edited to update their details or mark them as completed.</li>
    </ul>
  </li>
  <li><strong>Dynamic User Interface:</strong>
    <ul>
      <li>Todos are displayed with their title and due date in a concise format. Higher-priority tasks are highlighted.</li>
      <li>The interface allows users to expand a task to view or edit additional details, such as the full description.</li>
    </ul>
  </li>
  <li><strong>Task Deletion:</strong>
    <ul>
      <li>Users can easily delete a task, removing it from the project.</li>
    </ul>
  </li>
  <li><strong>Data Persistence:</strong>
    <ul>
      <li>The app automatically saves project and todo data to localStorage whenever a change is made (e.g., adding, updating, or deleting a todo).</li>
      <li>On page load, the app checks localStorage and restores any saved projects and tasks, ensuring data is preserved across sessions.</li>
    </ul>
  </li>
  <li><strong>Modular Code Structure:</strong>
    <ul>
      <li>The project is organized with a clear separation of concerns: application logic (e.g., creating and managing todos) is separated from DOM manipulation and rendering.</li>
    </ul>
  </li>
</ul>

