# To-Do App

A simple and lightweight To-Do list application built using Python and `tkinter`. This app allows users to add tasks, mark them as completed, delete tasks, and persist them across sessions by saving them to a text file (`tasks.txt`).

## Features

- Add tasks by typing in the input field or pressing "Enter".
- Toggle task completion (mark as completed or incomplete).
- Delete tasks.
- Tasks are saved to `tasks.txt` to persist across app restarts.
- The app loads tasks from the `tasks.txt` file when opened.
- Tasks that are marked as completed have a ` - Completed` label.
- Lines starting with `#` in the `tasks.txt` file are ignored and not loaded as tasks (used for comments or metadata).

## Requirements

- Python 3.x
- `tkinter` (comes pre-installed with Python)

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/zubair-ui/TODO-App.git
   ```
2. Navigate to the project directory:
   ```bash
   cd todo-app
   ```

## Usage

1. Run the app by executing the Python script:

   ```bash
   python TODO.ipynb
   ```

2. **Adding a Task**:
   - Type a task into the input field and either press the "Add Task" button or hit `Enter` to add it to the list.
3. **Marking a Task as Completed**:
   - Select a task from the list and press the "Complete/Incomplete Task" button to toggle its completion status.
4. **Deleting a Task**:

   - Select a task and press the "Delete Task" button to remove it from the list.

5. **Task Persistence**:
   - Tasks will be saved to `tasks.txt` automatically. If you restart the app, tasks from the file will be loaded.
6. **Ignoring Lines in `tasks.txt`**:
   - Any line in `tasks.txt` starting with `#` will be ignored by the app (useful for comments or metadata).

## `tasks.txt` File Format

The `tasks.txt` file stores tasks in a simple text format. Each task is on a new line, and tasks marked as completed will have ` - Completed` appended to them.

**Example:**

```
Buy groceries
Clean the house - Completed
# This is a comment and will be ignored
Finish homework
```
