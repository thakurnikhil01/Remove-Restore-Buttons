# Remove-Restore-Buttons
Certainly! Here’s a README file description for the project you’ve described. This will provide an overview of the project, how it works, and how to use it.

---

# Task List Management

## Overview

This project provides a simple task management interface using HTML, CSS, and JavaScript. The interface allows users to manage a list of tasks with the ability to remove all tasks and restore them to their original state.

## Features

- **Remove All Tasks**: Clears all tasks from the list with a single click.
- **Restore All Tasks**: Restores the list to its original state with predefined tasks.
- **Delete Individual Tasks**: Each task has a delete button that removes the specific task from the list.

## Getting Started

To get started with this project, clone the repository and open the `DomQ1.html` file in your web browser.

### Prerequisites

- A modern web browser (e.g., Chrome, Firefox, Edge) to view and interact with the web page.

### Installation

1. **Clone the Repository**:
   ```sh
   https://github.com/thakurnikhil01/Remove-Restore-Buttons.git
   ```
2. **Navigate to the Project Directory**:
   ```sh
   cd Remove-Restore-Buttons
   ```
3. **Open the `DomQ1.html` File**:
   Simply open the `DomQ1.html` file in your preferred web browser.

## Usage

1. **View the Task List**:
   When you open the page, you’ll see a list of tasks with "Delete" buttons next to each task.

2. **Remove All Tasks**:
   Click the **"Remove All"** button to clear all tasks from the list.

3. **Restore All Tasks**:
   Click the **"Restore All"** button to restore the list to its original state with the predefined tasks.

4. **Delete Individual Tasks**:
   Click the **"Delete"** button next to any task to remove that specific task from the list.

## Code Explanation

### HTML Structure

- **Buttons**:
  - **Remove All**: Clears the entire list of tasks.
  - **Restore All**: Restores the original list of tasks.
- **Task List**: An unordered list (`<ul>`) containing list items (`<li>`) with tasks and delete buttons.

### JavaScript Functionality

- **Element Selection**:
  - Select the buttons and list using `document.querySelector`.
  
- **Event Listeners**:
  - Attach click event listeners to the buttons.
  - `remove()`: Clears all list items.
  - `restore()`: Restores the list to its original state and reattaches delete event listeners.
  - `attachDeleteEventListener()`: Attaches click event listeners to delete buttons to remove individual tasks.

### JavaScript Functions

- **`attachDeleteEventListener()`**: 
  - Selects all delete buttons and attaches click event listeners to them.
  - Removes the parent `<li>` element when a delete button is clicked.

- **`remove()`**:
  - Removes all child elements from the task list.

- **`restore()`**:
  - Clears the list and sets its content to the original HTML.
  - Reattaches delete event listeners to the newly restored tasks.

## Contributing

Feel free to fork the repository and submit pull requests. Contributions are welcome!


---

Replace `https://github.com/yourusername/Remove-Restore-Buttons.git` with the actual URL of your GitHub repository.

This README file provides a comprehensive overview of the project, how to use it, and a brief explanation of the code for contributors and users.
