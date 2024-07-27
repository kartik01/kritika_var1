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


Installation

Clone the repository:

sh

git clone https://github.com/kritts12/kritika_var1
cd kritika_var1

Install the required libraries:

sh
pip install pyqrcode pillow

Usage
Run the application:

sh
python qrcode_generator.py
