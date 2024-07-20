# Flutter ToDo App

A simple ToDo application built with Flutter that allows users to add, delete, and search ToDo items.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Structure](#code-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add new ToDo items.
- Mark ToDo items as completed.
- Delete ToDo items.
- Search through ToDo items.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/flutter_todo_app.git
    cd flutter_todo_app
    ```

2. **Install dependencies:**

    ```bash
    flutter pub get
    ```

3. **Run the app:**

    ```bash
    flutter run
    ```

## Usage

- **Adding a ToDo:**
    - Enter the ToDo text in the input field at the bottom.
    - Press the `+` button to add the ToDo item to the list.

- **Marking a ToDo as completed:**
    - Tap on the ToDo item to mark it as completed or uncompleted.

- **Deleting a ToDo:**
    - Press the delete icon on the right side of the ToDo item to delete it.

- **Searching ToDos:**
    - Enter text in the search box to filter ToDo items.

## Code Structure

- **Main Entry Point:**
    - `main.dart`: Initializes the app and sets up the main `MyApp` widget.

- **Home Screen:**
    - `home.dart`: Contains the `Home` widget that displays the list of ToDo items and handles adding, deleting, and searching ToDos.

- **ToDo Model:**
    - `todo.dart`: Defines the `ToDo` class and provides a static method to generate a sample list of ToDos.

- **ToDo Item Widget:**
    - `todo_item.dart`: Defines the `ToDoItem` widget used to display individual ToDo items.

- **Constants:**
    - `colors.dart`: Defines custom colors used throughout the app.

### File Structure

lib/
│
├── constants/
│ └── colors.dart
│
├── model/
│ └── todo.dart
│
├── screens/
│ └── home.dart
│
├── widgets/
│ └── todo_item.dart
│
└── main.dart

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
