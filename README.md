# JSX-and-Components

Certainly! Here are three practice projects to help you practice JSX and components in React. I'll provide a brief overview of each project and then detailed step-by-step instructions.

**Project 1: Basic JSX Practice**

*Overview*: In this project, you'll create a simple React application to practice writing JSX and creating basic components.

**Step 1:** Set up your development environment.

1. Ensure you have Node.js and npm installed on your computer.
2. Create a new directory for your project.
3. Inside the project directory, run `npx create-react-app jsx-practice` to create a new React application.

**Step 2:** Create a simple component.

1. Inside the `src` folder, create a new file named `MyComponent.js`.
2. In `MyComponent.js`, define a functional component that returns a JSX element (e.g., a simple `<div>` with some text).

**Step 3:** Use the component in the main App component.

1. Open `src/App.js`.
2. Import `MyComponent` at the top of the file.
3. Replace the content of the `return` statement in the `App` component with an instance of `MyComponent`.

**Step 4:** Run the application.

1. In the project directory, run `npm start`.
2. Open your browser to view the simple React application using your custom component.

**Project 2: Creating a Navbar**

*Overview*: Build a basic navigation bar component using JSX.

**Step 1:** Set up a new React app (similar to Project 1).

**Step 2:** Create a Navbar component.

1. Inside the `src` folder, create a new file named `Navbar.js`.
2. In `Navbar.js`, create a functional component that renders a navigation bar with links (use the `<nav>` and `<ul>` elements).

**Step 3:** Use the Navbar component in your App.

1. Open `src/App.js`.
2. Import `Navbar` at the top of the file.
3. Replace the content of the `return` statement in the `App` component with an instance of `Navbar`.

**Step 4:** Style your Navbar using CSS.

**Project 3: Building a Simple To-Do List**

*Overview*: Create a basic to-do list using React components.

**Step 1:** Set up a new React app (similar to Project 1).

**Step 2:** Create a To-Do List component.

1. Inside the `src` folder, create a new file named `TodoList.js`.
2. Create a functional component that displays a list of to-do items.
3. Use JSX to render a list of items with checkboxes.

**Step 3:** Create a form for adding new to-do items.

1. Inside `TodoList.js`, add a form with an input field for entering new to-do items and a submit button.

**Step 4:** Implement basic interactivity.

1. Add state to your `TodoList` component to manage the list of to-do items.
2. Implement event handlers to add new items to the list when the form is submitted and update the state accordingly.

**Step 5:** Display and update the list.

1. Use JSX to map over the list of to-do items and display them.
2. Implement the ability to mark items as completed by changing their styles when clicked.

# CSS files

```
/* MyComponent.css */

.my-component {
  background-color: #f0f0f0;
  padding: 20px;
  border: 1px solid #ccc;
  text-align: center;
  font-size: 1.5rem;
}

```

```
/* Navbar.css */

.navbar {
  background-color: #333;
  color: white;
  padding: 10px 20px;
}

.navbar ul {
  list-style: none;
  padding: 0;
}

.navbar li {
  display: inline;
  margin-right: 20px;
}

.navbar a {
  text-decoration: none;
  color: white;
}
```


End of practice Projects
