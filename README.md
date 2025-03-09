**To-Do List App**
A simple and user-friendly To-Do List application built with React and styled with Tailwind CSS. This app allows you to add, delete, and store your to-dos locally so your list remains intact even after reloading.

**Features**
Add To-Do: Quickly add tasks to keep track of your daily activities.
Delete To-Do: Remove tasks once completed or if no longer needed.
Persistent Storage: Saves data to localStorage to retain your to-dos even after the browser refreshes.

**Demo**
N/A

**Installation**
Clone the repository

bash
Copy code
git clone https://github.com/your-username/todo-list-app.git
cd todo-list-app
Install dependencies

bash
Copy code
npm install
Run the app

bash
Copy code
npm start
Open http://localhost:3000 or your personalized localhost port to view it in your browser.

**Built With**
React - A JavaScript library for building user interfaces.
Tailwind CSS - A utility-first CSS framework.
Project Structure
/src
components - Contains reusable React components, including the To-Do List and individual To-Do item components.
App.js - The main app component where the app's logic resides.
index.js - The entry point of the application.

**How It Works**
Adding a To-Do: Enter a task in the input field and press Enter or click the "Add" button.
Deleting a To-Do: Click the delete button next to each task to remove it from the list.
Persistent Storage: The app utilizes the localStorage API to store the list of tasks, ensuring they remain visible after refreshing or reopening the app.

**Contributing**
If you would like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.
