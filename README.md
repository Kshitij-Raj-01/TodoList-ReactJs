<h1>ToDo List React JS Project</h1>
<h3>Home</h3>
<p>Welcome to the ToDo List ReactJS Project Wiki! This project is a simple, yet powerful task management application built using ReactJS. It allows you to add tasks with descriptions, mark them as completed, view completed tasks, and delete tasks.</p>

<h3>Table of Contents</h3>
<ul>
 <li>Overview</li>
 <li>Installation</li>
 <li>Usage</li>
 <li>Features</li>
 <li>Component</li>
 <li>Contributing</li>
</ul>
<h3>Overview</h3>
<p>The ToDo List project is designed to help users manage their tasks efficiently. Users can add new tasks with descriptions, mark tasks as completed, view a list of completed tasks, and delete tasks. The project demonstrates the use of ReactJS for building interactive user interfaces.</p>

<h3>Installation</h3>
Follow these steps to get the project up and running on your local machine.

<h4>Prerequisites</h4>
<ul>
 <li>Node.js (>=12.x)</li>
 <li>npm (>=6.x) or yarn (>=1.x)</li>
</ul>
<h4>Steps</h4>
<ol>
 <li>Clone the repository</li>

```
git clone https://github.com/Kshitij-Raj-01/TodoList-ReactJs.git
cd TodoList-ReactJs
```

<li>Install dependencies</li>


```
npm install
# or
yarn install
```

<li>Start the development server</li>

```
npm start
# or
yarn start
```

Open http://localhost:3000 to view it in the browser.
</ol>

<h3>Usage</h3>
<h4>Adding a Task</h4>
<ol>
 <li>Enter the task title and description in the input fields.</li>
 <li>Click the "Add" button.</li>
</ol>
<h4>Completing a Task</h4>
<ol>
 <li>Click the checkbox next to the task title.</li>
 <li>The task will be moved to the "Completed Tasks" section.</li>
</ol>
<h4>Viewing Completed Tasks</h4>
<ul>
<li>Navigate to the "Completed Tasks" page to view all tasks marked as completed.</li>
</ul>
<h4>Deleting a Task</h4>
<ul>
<li>Click the delete icon (🗑️) next to the task title to remove the task.</li>
</ul>
<h3>Features</h3>
<ul>
<li><b>Add Tasks</b>: Add new tasks with titles and descriptions.</li>
<li><b>Complete Tasks</b>: Mark tasks as completed.</li>
<li><b>View Completed Tasks</b>: View a list of all completed tasks.</li>
<li><b>Delete Tasks</b>: Remove tasks from the list.</li>
</ul>
<h3>Components</h3>
<h4>TaskInput</h4>
<ul>
<li><b>Description</b>: Component for adding new tasks.</li>
<li><b>Props</b>:</li>
<ul>
<li><b>handleAddTodo</b> (Array): Function to call for add the new tasks.</li>
</ul>
</ul>
<h4>TaskList</h4>
<ul>
<li><b>Description</b>: Component for displaying the list of tasks.</li>
<li><b>Props</b>:</li>
<ul>
<li><b>allTodos</b> (Array): List of tasks to display.</li>
<li><b>handleCompleteTodo</b> (Function): Function to call when a task is completed.</li>
<li><b>handleDeleteTodo</b> (Function): Function to call when a task is deleted.</li>
</ul>
</ul>
<h4>TaskItem</h4>
<ul>
<li><b>Description</b>: Component for displaying a single task.</li>
<li><b>Props</b>:</li>
<ul>
<li><b>handleCompleteTodo</b> (Function): Function to call when the task is completed.</li>
<li><b>handleDeleteTodo</b> (Function): Function to call when the task is deleted.</li>
</ul>
</ul>
<h3>CompletedTasks</h3>
<ul>
<li><b>Description</b>: Component for displaying completed tasks.</li>
<li><b>Props</b>:</li>
<ul>
<li><b>completedTodos</b> (Array): List of completed tasks.</li>
</ul>
</ul>
<h3>Contributing</h3>
<p>We welcome contributions to the project. Please follow these steps to contribute:</p>
<ol>
<li>Fork the repository.</li>
<li>Create a new branch <b>(git checkout -b feature-branch).</b></li>
<li>Make your changes.</li>
<li>Commit your changes <b>(git commit -m 'Add some feature').</b></li>
<li>Push to the branch <b>(git push origin feature-branch).</b></li>
<li>Create a new Pull Request.</li>
