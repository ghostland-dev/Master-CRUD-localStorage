# LocalStorage Task Manager
![SCREEN](https://github.com/Ismail-Mouyahada/Master-CRUD-localStorage/assets/66369128/0180d1ef-c5c7-45bb-a3d8-f02446c32f19)

This project is a simple task manager that utilizes the browser's localStorage to store and manage tasks. The application allows users to add, view, modify, and delete tasks, with a user-friendly interface built using UIkit.

## Features

- Add new tasks with a title.
- View the list of tasks.
- Modify existing tasks.
- Delete individual tasks or clear all tasks.
- Print the list of tasks.
- Simple encryption and decryption functions for handling data.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- UIkit (CSS framework)

## Getting Started

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/ismail-mouyahada/localstorage-task-manager.git
    ```
2. **Navigate to the project directory:**
    ```sh
    cd localstorage-task-manager
    ```
3. **Open the `index.html` file in your preferred web browser.**

## File Structure

- `index.html`: Main HTML file containing the structure and logic for the task manager.
- `styles.css`: (Optional) Custom styles for the project.
- `scripts.js`: (Optional) External JavaScript file for the project logic.

## How It Works

### Adding a Task

1. Enter the task title in the input field.
2. Click the "Enregistrer" button to save the task.
3. The task is saved to `localStorage` and displayed in the task list.

### Viewing Tasks

- The task list is displayed in a table format.
- Each task shows its title, the date it was added, and options to view, modify, or delete the task.

### Modifying a Task

1. Click the "Modifier" button next to a task.
2. Enter the new value in the input field in the modal that appears.
3. Click "Enregistrer les modifications" to save the changes.

### Deleting a Task

1. Click the "Effacer" button next to a task.
2. Confirm the deletion in the modal that appears.

### Clearing All Tasks

- Click the "Tout Supprimer" button to clear all tasks from `localStorage`.

### Printing Tasks

- Click the "Imprimer" button to print the list of tasks.

## Encryption and Decryption

- The `hash` function encrypts task data by converting each character to its ASCII value.
- The `unhash` function decrypts the data by comparing the stored and submitted values.

## Code Overview

### HTML

The HTML file contains the structure for the task manager, including the form for adding tasks and the table for displaying tasks.

### JavaScript

The JavaScript code handles the following:

- Adding tasks to `localStorage`.
- Retrieving and displaying tasks from `localStorage`.
- Modifying and deleting tasks.
- Simple encryption and decryption of task data.

### UIkit

UIkit is used for styling the application, providing a clean and responsive user interface.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to improve the project.

## Acknowledgements

- [UIkit](https://getuikit.com/) for the UI components.
- [Pexels](https://www.pexels.com/) for the example image.

