# iTask: Simple To-Do List Manager

![iTask Logo](public/todo-list.webp)

iTask is a straightforward and intuitive web application designed to help you manage your daily tasks efficiently. Built with React and styled using Tailwind CSS, it offers a clean interface for adding, editing, deleting, and tracking your to-do items.

## Table of Contents

* [Features](#features)
* [Technologies Used](#technologies-used)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
    * [Installation](#installation)
    * [Running the Application](#running-the-application)
* [Project Structure](#project-structure)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

## Features

* **Add New Todos:** Quickly add new tasks to your list.
* **Edit Todos:** Modify existing tasks with ease.
* **Delete Todos:** Remove completed or unwanted tasks.
* **Mark as Completed:** Toggle the completion status of tasks.
* **Show/Hide Finished Tasks:** Filter your view to only see unfinished tasks or all tasks.
* **Persistent Storage:** Your to-dos are saved locally in your browser's `localStorage`, so they persist even if you close the tab or browser.
* **Responsive Design:** The application is designed to be user-friendly on various screen sizes.
* **Clean UI:** A minimalist and modern user interface powered by Tailwind CSS.

## Technologies Used

* **React:** A JavaScript library for building user interfaces.
* **Vite:** A fast build tool that provides a lightning-fast development experience for modern web projects.
* **Tailwind CSS:** A utility-first CSS framework for rapidly building custom designs.
* **React Icons:** A library providing popular icons (FaEdit, AiFillDelete).
* **UUID:** For generating unique IDs for each to-do item.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before you begin, ensure you have the following installed:

* **Node.js & npm (or yarn):** Download from [nodejs.org](https://nodejs.org/).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Akshith-M-Naik/todo-manager.git](https://github.com/Akshith-M-Naik/todo-manager.git) # Replace with your actual repo URL if different
    cd todo-manager # Or the name of your project directory
    ```
2.  **Install dependencies:**
    Navigate to the root directory of the project where `package.json` is located and run:
    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Application

1.  **Start the development server:**
    From the project's root directory, run:
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    This command will start the Vite development server.

2.  **Access the application:**
    Open your web browser and navigate to the URL displayed in your terminal (e.g., `http://localhost:5173`).

### Building for Production

To create a production-ready build of the application:
```bash
npm run build
# or
yarn build
```
This will generate optimized static assets in the `dist` directory, which you can then deploy to any static web hosting service.

## Project Structure

```
todo-manager/
├── public/
│   └── todo-list.webp     # Application icon/logo
├── src/
│   ├── components/
│   │   └── Icon.jsx       # Component for the iTask logo and title
│   ├── App.jsx            # Main application component (handles todo logic and UI)
│   ├── index.css          # Tailwind CSS import and global styles
│   └── main.jsx           # React app entry point
├── .eslintrc.js           # ESLint configuration
├── index.html             # Main HTML file
├── package.json           # Project dependencies and scripts
├── package-lock.json      # Dependency tree lock file
└── vite.config.js         # Vite configuration (React and Tailwind plugins)
```

## Usage

1.  **Add a Todo:** Type your task in the input field and click the "Save" button. The "Save" button will be enabled once you type more than 3 characters.
2.  **Edit a Todo:** Click the pencil icon next to a task to edit its content. The task will appear in the input field for modification.
3.  **Delete a Todo:** Click the trash can icon next to a task to remove it from the list.
4.  **Mark as Completed:** Click the checkbox next to a task to mark it as completed. Completed tasks will have a strikethrough.
5.  **Show/Hide Finished:** Use the "Show Finished" checkbox to toggle the visibility of completed tasks.

## Contributing

We welcome contributions to iTask! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add new feature'`).
5.  Push to the branch (`git push origin feature/your-feature-name`).
6.  Open a Pull Request.

Please ensure your code adheres to the existing style and includes appropriate tests if applicable.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Contact

For any questions or inquiries, please feel free to reach out to the repository owner.
