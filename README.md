# Python To-Do List Application

This simple command-line To-Do List application demonstrates fundamental Python programming concepts and provides basic task management functionality.

## Features

- Add tasks to the list
- Remove tasks from the list
- Display all tasks
- Persistent storage (tasks are saved between sessions)

## Concepts Demonstrated

1. **Object-Oriented Programming (OOP)**: The application uses a `TodoList` class to encapsulate data and methods.
2. **File I/O**: Tasks are saved to and loaded from a text file, demonstrating file handling in Python.
3. **User Input Handling**: The program takes and processes user input in a loop.
4. **Basic Error Handling**: The application includes simple error checking (e.g., for valid menu choices).
5. **Command-Line Interface**: Demonstrates creating a simple text-based user interface.

## How to Use

1. Ensure you have Python installed on your system (Python 3.x recommended).
2. Clone this repository or download the `todo_list.py` file.
3. Open a terminal or command prompt and navigate to the directory containing `todo_list.py`.
4. Run the script by entering:
   ```
   python todo_list.py
   ```
5. Follow the on-screen prompts to interact with the application:
   - Enter '1' to add a new task
   - Enter '2' to remove a task
   - Enter '3' to display all tasks
   - Enter '4' to quit the application

## Note

Tasks are automatically saved to a file named `tasks.txt` in the same directory as the script. This file will be created if it doesn't exist and updated as you add or remove tasks.

## Future Enhancements

Potential areas for expanding this project include:
- Adding due dates to tasks
- Implementing task priorities
- Creating a graphical user interface (GUI)
- Adding task categories or tags

Feel free to fork this project and add your own enhancements!
