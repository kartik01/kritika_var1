# kritika_var1

# Password Generator

## Overview

This is a simple and user-friendly Password Generator application built using Python's Tkinter library. The application allows users to generate strong and secure passwords. Users can easily copy the generated passwords to the clipboard for use in other applications.

## Features

- **Graphical User Interface**: Easy-to-use interface with Tkinter.
- **Customizable Length**: Choose password lengths between 4 and 12 characters.
- **Diverse Characters**: Passwords include uppercase letters, lowercase letters, digits, and punctuation symbols.
- **Copy to Clipboard**: Quickly copy the generated password to the clipboard with a single click.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/kritts12/kritika_var1
    cd kritika_var1
    ```

2. **Install the required packages**:
    Ensure you have Python installed. You also need the `pyperclip` package, which can be installed using:
    ```bash
    pip install pyperclip
    ```

3. **Run the application**:
    ```bash
    python password_generator.py
    ```

## Usage

1. Open the application.
2. Select the desired password length using the spinbox.
3. Click the "Generate" button to create a password.
4. The generated password will be displayed in the text field.
5. Click "Copy to Clipboard" to copy the password for use.



# QR Code Generator

This project is a simple QR code generator built using Python, Tkinter, and the pyqrcode library. The application provides a graphical user interface (GUI) that allows users to input text and generate a corresponding QR code. The generated QR code is displayed within the application window and saved as a PNG file.

## Features

- **User-friendly Interface:** A straightforward GUI built with Tkinter.
- **Text Input:** Users can enter any text to generate a QR code.
- **QR Code Generation:** Generates a QR code from the provided text and saves it as a PNG file.
- **QR Code Display:** Displays the generated QR code directly in the application window.
- **Error Handling:** Alerts users if the text input is empty.

## Prerequisites

Ensure you have Python installed on your system. You will also need to install the following libraries:
- `pyqrcode`
- `pillow` (PIL)

You can install these libraries using pip:
```sh
pip install pyqrcode pillow
```

Installation

Clone the repository:

git clone https://github.com/kritts12/kritika_var1
cd kritika_var1

Install the required libraries:

pip install pyqrcode pillow

Usage
Run the application:

python qrcode_generator.py


# To-Do List Application

This Python script creates a simple To-Do List application using the Tkinter library. The application interface consists of five tasks, each with a corresponding checkbox and text entry field. The tasks can be marked as complete using the checkboxes and saved using a "Save" button. The script captures the text from the entry fields and prints it in the console when the "Save" button is pressed.

## Key Components
- **Checkbuttons**: Allow users to mark tasks as complete.
- **Entry Widgets**: Provide input fields for users to type their tasks.
- **Button**: Triggers the `get_text` function to save and print the entered tasks.

## Layout
- The layout is managed using the `grid` method, with each task and its checkbox arranged in a row.
- The window has a title "To Do List" and is set to a size of 500x500 pixels.

## Functionality
- The `get_text` function retrieves the text from each entry widget and stores it in a dictionary called `entry_data`.
- When the "Save" button is clicked, the `get_text` function is executed, and the task data is printed in the console.

## How to Run
1. Ensure you have Python installed on your system.
2. Save the script as `to_do.py`.
3. Run the script using the command:
    ```bash
    python to_do.py
    ```
4. A window will appear with five entry fields and corresponding checkboxes.
5. Enter your tasks in the fields and click "Save" to print the tasks to the console.

This project provides a basic yet functional example of how to create a GUI application with Tkinter.

