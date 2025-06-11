# To-Do-List-

✅ To-Do List Web App using HTML, CSS & JavaScript
This is a simple and interactive To-Do List application built with HTML, CSS, and JavaScript. It allows users to add, edit, and delete tasks dynamically in a clean, user-friendly interface. Each task entry is timestamped for better organization.

🔧 Key Features and Functionality:
Add Task Functionality: Clicking the "Add Task" button appends a new editable task with the current date and time.

Edit Tasks Inline: Users can click "Edit" to focus and modify the task directly using contenteditable.

Delete Tasks Instantly: Tasks can be removed using the "Delete" button with real-time feedback.

Auto Timestamping: Each new task logs the current date and time using JavaScript’s Date object.

Responsive Centered Layout: Styled using flexbox to center the task container vertically and horizontally on any screen size.

🧠 How it Works:
HTML Structure:

Contains a container <div> for the task list and an "Add Task" button.

Tasks are dynamically added to an unordered list (<ul>).

CSS Styling:

Uses a modern card layout with rounded corners, shadows, and clean spacing.

Custom buttons for "Add", "Edit", and "Delete" actions with color-coded styling.

JavaScript Logic:

addTodo(): Creates a new task with editable text, timestamp, and action buttons.

editTodo(): Focuses the task text for inline editing.

deleteTodo(): Removes the task element from the DOM.

