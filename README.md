# RadioButton Demo Application

## Overview
The **RadioButton Demo Application** is a simple GUI application developed using Python's `tkinter` library. This program demonstrates the usage of `Radiobutton` widgets to allow users to select one option from a group of options and displays the selected option when the "OK" button is pressed.

## Features
- Three `Radiobutton` widgets for selecting options.
- An "OK" button to confirm the selection and display it in a message box.
- A "QUIT" button to exit the application.
- Utilizes `tkinter` for creating the GUI.

## Code Structure
The application is encapsulated in a class named `MyGUI` and includes the following components:

### Variables
- `main_window`: The main window of the application.
- `top_frame`, `bottom_frame`: Frames to organize the layout of `Radiobutton` and button widgets.
- `radio_var`: An `IntVar` object to store the value of the selected `Radiobutton`.

### Methods
- `__init__()`: Constructor to initialize the main window, frames, `Radiobutton` widgets, and buttons. It also packs the widgets and starts the main loop.
- `show_choice()`: Callback method for the "OK" button. Displays a message box with the selected option.

### Widgets
- `Radiobutton`: Three `Radiobutton` widgets in the `top_frame` to present the options to the user.
- `Button`: An "OK" button to display the selected option and a "QUIT" button to close the application.

## Getting Started

### Prerequisites
- Python (version 3.6 or higher)
- `tkinter` library (comes pre-installed with Python)

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/RadioButtonDemo.git
    ```
2. Navigate to the project directory:
    ```sh
    cd RadioButtonDemo
    ```

### Usage
1. Run the application:
    ```sh
    python demo.py
    ```
2. Select one of the options using the `Radiobutton` widgets.
3. Click the "OK" button to display the selected option in a message box.
4. Click the "QUIT" button to exit the application.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Author
- Leslie

Feel free to reach out for any questions or contributions. Happy coding!

---

### Note
This application is a simple demonstration intended for learning and showcasing basic `tkinter` functionality. It may require further enhancements for more complex use cases.
