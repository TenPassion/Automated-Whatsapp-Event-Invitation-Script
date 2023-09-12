# Automated WhatsApp Message Sender

This project is a Python application that allows you to automate sending WhatsApp messages from Excel files with prepared messages and attached images.

## Table of Contents

1. [Requirements](#requirements)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Code Description](#code-description)
5. [Contribution](#contribution)
6. [License](#license)

## Requirements

Make sure you have the following dependencies installed on your system:

- Python 3.x
- pywinauto
- pyperclip
- pyautogui
- Pillow
- win32clipboard

## Installation

1. Clone this repository to your machine:

```shell
git clone https://github.com/your-username/automated-whatsapp-sender.git
```

Navigate to the project directory:

```shell
cd automated-whatsapp-sender
Install the required dependencies:
```
shell
Edit

Run
Append
Copy
pip install -r requirements.txt
Usage
Ensure you have prepared your Excel files, messages, and images in the appropriate directories:

./excels for Excel files
./messages for prepared messages
./images for attached images
Run the program using the following command:


shell
Edit

Run
Append
Copy
python main.py
Follow the program's instructions to choose the actions to perform.
Code Description
The code is organized as follows:

The program initializes by creating directories for Excel files, messages, and images if they do not exist already.

It provides a menu for users to choose from several functions:

Upload Excel: Select an Excel file to use for message sending.
Draft a Message: Compose a prepared message in Notepad.
Send a Message: Send WhatsApp messages using Excel files, prepared messages, and attached images.
Upload Image: Select images to use in messages.
Exit: Quit the program.
The code leverages various libraries such as pywinauto, pyperclip, pyautogui, Pillow, and win32clipboard for GUI automation, clipboard operations, and image handling.

Detailed comments and prompts are provided throughout the code to guide users and explain its functionality.

Contribution
If you wish to contribute to this project, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Note: Make sure to comply with WhatsApp's rules and regulations when using this application.
